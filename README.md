# Transfacts HTF Database site

Website with complete human transcription factor database allowing users to get information from uploaded GDS files and background information on human transcription factors and associated drugs.

URL : http://transfacts.eu-west-2.elasticbeanstalk.com/

## Getting Started

Local: Download a zip of this repository, open it and export application.py as FLASK_APP. You can then 'flask run' in CLI to run the application.

### Prerequisites

What things you need to install the software and how to install them

R needs to be installed for rpy2 package to function. Check https://www.r-project.org/

```
pip install -r /path/to/requirements.txt
```
SQLite needs to be downloaded and installed. Check https://www.sqlite.org/download.html


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

Set FLASK_APP

MacOS:
```
export FLASK_APP=/path/to/application.py
```

And Windows 

```
$env:FLASK_APP = "application.py"
```

Then load the site on your localhost url using:

```
flask run
```

To download the database, run the scripts in the folder database in order.

## Deployment

Connect GitHub to Elastic Beanstalk via CodePipeline or upload the zip as a source code bundle. Please ensure R is on the EB instance (see our documentation for details on commands)

## Built With

* [Elastic Beanstalk](https://docs.aws.amazon.com/elastic-beanstalk/index.html) - The web framework used



## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Alejandra Carriero** - *Database development* - [alcarrie](https://github.com/alcarrie)
* **Amanda Ho-Lyn** - *Web Design and AWS deployment* - [acholyn](https://github.com/acholyn)
* **Muhammad Rahman** - *Flask Deployment and integration of R into Python* - [mfrahman123](https://github.com/mfrahman123)
* **Lahiru Thomas Sooriyabandara** - *GDS Data Analysis and TFA Calculations* - [ltom1000](https://github.com/ltom1000)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Bootstrap
* DataTables
* Conrad Bessant
* Fabrizio Smeraldi
* Millahat Asif
