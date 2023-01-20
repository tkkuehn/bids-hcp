# HCP Unrelated 100 BIDS Subset (BIDS-HCP)

This dataset contains imaging data from a subset (n=30) of the Human Connectome Project, reorganized into BIDS.

This subset consists of 30 unrelated healthy subjects (age: 21-52; 15 female and 15 male) chosen from the Human Connectome Project dataset (HCP). All scans were T1-weighted MR volumes with 1 mm voxels acquired on a 3-T scanner.

This dataset is intended for use with the "Ground truth AFIDs-HCP" dataset, available at (DOI here), both released as part of the AFIDs-Data project (DOI here).

## Data Use Agreement

These images are released under the [WU-Minn HCP Consortium Open Access Data Use Terms](./DATA_USE_AGREEMENT.md).

## Access

The DataLad image links are adapted from the existing Human Connectome Project Open Access DataLad dataset (https://github.com/datalad-datasets/human-connectome-project-openaccess). The following data access and retrieval instructions are taken from that dataset's readme.

To retrieve HCP Open Access data via DataLad with this dataset, you need to agree
to the [WU-Minn HCP Consortium Open Access Data Use Terms](./DATA_USE_AGREEMENT.md)
and obtain valid AWS credentials:

- Create an account at http://db.humanconnectome.org.
- Log into your account and accept the data use terms of the "WU-Minn HCP Data -
  1200 Subjects" data release.
- Enable Amazon S3 access for your Amazon account to get an access key ID
  and a secret access secret key (click on the button with the S3 logo).
  - The access key ID is a character string similar to this: ``AKIAXOX5CT57GHZ4SVFV``
  - The secret access key is a character string similar to this: ``vntFcVA+YI0Ii3tVZPpdyQrgp2H05YjesyXKGE+n``

You will be asked to supply your AWS credentials the first time you use `datalad get`
to retrieve file content of your choice from
the [HCP Open Access dataset](https://registry.opendata.aws/hcp-openaccess/). You
should only need to provide credentials once, and all subsequent `datalad get` commands
will retrieve data without asking them again.

Data were provided by the Human Connectome Project, WU-Minn Consortium (Principal Investigators: David Van Essen and Kamil Ugurbil; 1U54MH091657) funded by the 16 NIH Institutes and Centers that support the NIH Blueprint for Neuroscience Research; and by the McDonnell Center for Systems Neuroscience at Washington University.

IMPORTANT: Please note that by downloading and using imaging data in this dataset, you confirm that you have read and agreed to the WU-Minn HCP Consortium Open Access Data Use Terms outlined here: https://www.humanconnectome.org/study/hcp-young-adult/document/wu-minn-hcp-consortium-open-access-data-use-terms. 
