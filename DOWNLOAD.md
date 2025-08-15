Dataset **Makassar Road** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjQ4OF9NYWthc3NhciBSb2FkL21ha2Fzc2FyLXJvYWQtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiRWttTExSc1VSVmVTZUZLMU1LVlRQa1NYeUVRZEUxeTJJeTZ1UVRLcVVxUT0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22makassar-road-DatasetNinja.tar%22)

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

