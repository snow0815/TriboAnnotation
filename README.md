
For working with the environment you should install [Anaconda](https://www.anaconda.com/products/individual). You need to create an environment for each module. The quick access can be done using the powershell prompt within the conda environment. For more information about dealing with conda environments refer to https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html.

## Quick Access

A quick access to the pipeline is provided through the pre-analysed publications provided within the GUI. For working with the Web-Interface follow the steps:

1. Go to folder **[semantic_annotation_pipeline-ui](https://github.com/ReneDorsch/semantic_annotation_pipeline-ui.git)**, download the Code and extract the .zip in a new directory: ...\semantic_annotation_pipeline-ui
2. Create a new conda Environment <code>conda create -n NEW_ENVIRONMENT_NAME</code>
3. Activate the new environment <code>conda activate NEW_ENVIRONMENT_NAME</code> and navigate to the folder of the semantic annotation pipeline: <code>cd ...\semantic_annotation_pipeline-ui</code>
4. Install the requirements <code>pip install -r requirements.txt</code>
5. Run the Pipeline: <code>python main.py </code>

## Usage and License

The content provided within this repository is free to share and adapt under CC BY 4.0.  
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
