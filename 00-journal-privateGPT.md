# INSTALLING PRIVATE GPT LOCALLY

https://docs.privategpt.dev/#section/Installation-and-Settings


`$conda activate privategpt`
    privategpt environment installed



## INSTALLATION PROCESS

   https://docs.privategpt.dev/installation 

### poetry 
  installed
    to use local version of private gpt

  `$poetry install --with ui`
  `$poetry install --with local`


### Setup LLMs
  Before running the setup you can set which model to be downloaded
  That settings can be done in "settings.yaml" file.

  `$poetry run python scripts/setup`
    default LLMs are installed on my machine


### GPU setup (win)

  download CUDA: https://developer.nvidia.com/cuda-downloads?target_os=Windows 

  CUDA driver installed
      Visual Studio installed

  check CUDA install and detect GPU
    `$ nvcc --version`
    `$ nvidia-smi`     (bosluk yok)

done.



=================================================
# USAGE    (https://docs.privategpt.dev/manual)
=================================================
Use one of the profiles:
    Windows Powershell(s) have a different syntax, one of them being:

        `$ set PGPT_PROFILES=local`


Launch the privateGPT API server **and** the gradio UI
   `$ poetry run python private_gpt`


In another terminal, create a new browser window on your private GPT!
open http:////127.0.0.1:8001/
or localhost:8001


