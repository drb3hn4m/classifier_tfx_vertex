# classifier_tfx_vertex
1) create an instance in USER-MANAGED NOTEBOOKS in the Workbnach of Vertex ai. THe machine specification could be "Efficient Instance: 4 vCPUs, 16 GB RAM"
2) open the jupyterlab and then open a terminal and clone the current repository. 
3) open the 'vertex_pipeline.ipynb' notebook and follow the steps. the steps up to deployment to the endpoint are mostly based on Simple [TFX Pipeline example](https://www.tensorflow.org/tfx/tutorials/tfx/penguin_simple)
MAKE SURE that replace the 'GOOGLE_CLOUD_PROJECT' and 'GOOGLE_CLOUD_REGION' with what is required.
GOOGLE_CLOUD_PROJECT should be already linked to a billing account, if not followin the instruction in [som_project repo](https://github.com/drb3hn4m/som_project)
ALSO note that GOOGLE_CLOUD_REGION is not zone! it's region!
- __Important note!__ make sure to delete all resources created on gcp vertex ai and google storage to avoid paying cost. You can find the used resouces from billing service

