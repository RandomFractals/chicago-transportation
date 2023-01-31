# Chicago Transportation EDA

Exploratory data analysis of public [Chicago transportation datasets](https://data.cityofchicago.org/browse?category=Transportation) from [Chicago Data Portal](https://data.cityofchicago.org/).

## Traffic Crashes

Chicago Data Portal provides traffic crash report information from all police districts starting from September 2017 to present, with data updated daily. [Traffic Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if) data from electronic crash reporting system (E-Crash) are available for some police districts in 2015, but citywide data are not available until September 2017.

![Chicago Traffic Crashes 2015 to Present Data Info ...](https://github.com/RandomFractals/chicago-transport/blob/main/docs/images/chicago-traffic-crashes-dataset.png?raw=true
 "Chicago Traffic Crashes 2015 to Present Data Info ...")

Crash data shows information about each traffic crash on city streets within the City of Chicago limits and under the jurisdiction of Chicago Police Department (CPD). About half of all crash reports, mostly minor crashes, are self-reported at the police district by the driver(s) involved and the other half are recorded at the scene by the police officer responding to the crash.

Many of the crash parameters, including street condition data, weather condition, and posted speed limits, are recorded by the reporting officer based on best available information at the time, but may disagree with posted information or other assessments on road conditions. A traffic crash within the city limits for which CPD is not the responding police agency, typically crashes on interstate highways, freeway ramps, and on local roads along the City boundary, are excluded from this dataset.

All crashes are recorded as per the format specified in the Traffic Crash Report, SR1050, of the Illinois Department of Transportation. The crash data published on the Chicago data portal mostly follows the data elements in SR1050 form. The current version of the SR1050 instructions manual with detailed information on each data elements is available [here](https://idot.illinois.gov/Assets/uploads/files/Transportation-System/Manuals-Guides-&-Handbooks/Safety/Illinois%20Traffic%20Crash%20Report%20SR%201050%20Instruction%20Manual%202019.pdf).

As per Illinois statute, only crashes with a property damage value of $1,500 or more or involving bodily injury to any person(s) and that happen on a public roadway and that involve at least one moving vehicle, except bike dooring, are considered reportable crashes. However, CPD records every reported traffic crash event, regardless of the statute of limitations, and hence any formal Chicago crash dataset released by Illinois Department of Transportation may not include all the crashes listed here.

Only crashes with a property damage value of $1,500 or more or involving bodily injury to any person(s) and that happen on a public roadway and that involve at least one moving vehicle, except bike dooring, are considered reportable crashes. However, CPD records every reported traffic crash event, regardless of the statute of limitations, and hence any formal Chicago crash dataset released by Illinois Department of Transportation may not include all the crashes listed in Traffic Crashes dataset.

### Traffic Crashes Data

You can download Chicago Traffic Crashes data in `CSV` format from the **Export** menu on the [crashes web page](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if):

![Chicago Traffic Crashes Data Download](https://github.com/RandomFractals/chicago-transport/blob/main/docs/images/chicago-traffic-crashes-data-export.png?raw=true
 "Chicago Traffic Crashes Data Download")

**Note**: as of 2003-01-31 Chicago Traffic Crashes dataset `CSV` is about 362 MB and contains over 691K traffic crash reports with 49 columns describing crash details, road and weather conditions, injuries and damages.