# Satellite Images Processing: Overview

### General references and links

Satellite platforms can acquire data with a moltitude of sensors. The ones involved in the Challenge are multi-band optical sensors.

For an example about how fully processed data displays, you can have a look one of the different public repositories: [Landsat 8 published on AWS](https://aws.amazon.com/public-datasets/landsat/).
The only requirements to access the full dataset is to have a AWS account and create an application token to use with AWS' client `boto3`. The Challenge provides similar data
but provided by Planet and ESA both accessible through the PlanetExplorer Web application or command-line client. This repository requires credentials that will be provided
during the project duration.

Landsat 8 is the best dataset to learn the basics. The [first example in the documentation](https://landsat-pds.s3.amazonaws.com/c1/L8/139/045/LC08_L1TP_139045_20170304_20170316_01_T1/index.html) provides
[this preview](https://landsat-pds.s3.amazonaws.com/c1/L8/139/045/LC08_L1TP_139045_20170304_20170316_01_T1/LC08_L1TP_139045_20170304_20170316_01_T1_thumb_large.jpg). The preview is just a JPEG "thumbnail"
of the real deal that are the different bands listed below in the page.

In the "Files" list you can see a list of the available files from the different bands: "BQA" and "B1" to "B10". To know on which section of 
the Electro-Magnetic Spectrum each band has been acquired you can read the [table here](https://landsat.usgs.gov/what-are-band-designations-landsat-satellites):

