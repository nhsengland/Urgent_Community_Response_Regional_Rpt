# Urgent Community Response (UCR) Regional Report
## NHS England Digitial Analytics and Research Team - PhD Internship Project

### About the Project

This repository holds code for the regional anal;ysis of UCR data.


_**Note:** Only public or fake data are shared in this repository._

### Project Stucture

- The main code is found in the root of the repository (see Usage below for more information)


### Built With

{LIST SOFTWARE USED TO CREATE PROJECT}

[R Studio](http://www.rstudio.com/.)  
[R Statistical Software](https://www.R-project.org/.)  
[SQL SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)  

- library(tidyverse)
- library(janitor)
- library(NHSRplotthedots)
- library(gt)
- library(gtExtras)
- library(odbc)
- library(glue)


### Getting Started

#### Installation

To get a local copy up and running follow these simple steps.

To clone the repo:

`git clone https://github.com/nhsengland/Urgent_Community_Response_Regional_Rpt`

### Usage

Code contains SQL query to pull data from UDAL warehouse.

You will need to create your own personal_creds.R file 

This will need to contain two variables

serv <- "{connection_string_to_warehouse}"
id <- "user_name@udal.nhs.uk"


#### Outputs
The output is a HTML report that shows analysis of reginal and local ICB performance and activty for UCR



#### Datasets
The dataset is in a UKHF table within UDAL and requires no additional access beyond stand NHSE access.

I will post a data cut in a .csv to support testing of this code in due course.

### Roadmap

This is designed to be part of a wider community information pack.

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

_See [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidance._

### License

Unless stated otherwise, the codebase is released under [the MIT Licence][mit].
This covers both the codebase and any sample code in the documentation.

_See [LICENSE](./LICENSE) for more information._

The documentation is [© Crown copyright][copyright] and available under the terms
of the [Open Government 3.0][ogl] licence.

[mit]: LICENCE
[copyright]: http://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/crown-copyright/
[ogl]: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

### Contact

To find out more about the South West Intelligence and Insights Team visit our [South West Intelligence and Insights Team Futures Page](https://future.nhs.uk/SouthWestAnalytics)) or get in touch at [england.southwestanalytics@nhs.net](mailto:england.southwestanalytics@nhs.net).

<!-- ### Acknowledgements -->



