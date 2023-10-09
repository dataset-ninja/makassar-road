Dataset **Makassar Road** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/L/T/RZ/zW0kqR4IlvzhdkdEqF4CTflolk8KWxxVKKT2PWRTdoM83yx3ein4nVFIummSY5Q45Y0JIwiutRRBj1loZYRalu4LwTxSRMmVeo1jKLfpELgYcaZcvkTG4PBwL7qs.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Makassar Road', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

