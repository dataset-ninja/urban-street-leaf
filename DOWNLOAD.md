Dataset **Urban Street: Leaf** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/J/if/0jSDmI9oZTLz8V6nK1yqxYiwTb0k9BTmqMBtPwsEkUkNq214ZNWzEytgeJa7JxDrV2n5T7HerpqOG4qAm0w03zuTTiAVaQPAU7f68lIzHZ4nZzdN0GElTjJdRKgb.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Urban Street: Leaf', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

