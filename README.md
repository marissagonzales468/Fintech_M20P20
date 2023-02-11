##JointSavings Smart Contract
To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.
## Technologies
This project leverages python 3.7 and requires Anaconda (the conda package manager should be complete..)

## Creating a NewEnv 
1. Open up either Terminal (Mac) or GitBash (Windows).
2. Check the Conda version that is installed by typing conda --version at the command prompt.
3. Update Conda by running the update command conda update conda. If a newer version is available, accept the update by typing y.
4. Update Anaconda by running the update command conda update anaconda. If a newer version is available, accept the update by typing y.
5.To create the conda dev environment, type the following: conda create -n dev python=3.7 anaconda. When prompted, choose y to proceed. The following image should appear in the Terminal/GitBash window:
![anaconda_dev_env](https://user-images.githubusercontent.com/113739944/218256401-40d6e7a4-d2e0-4028-8bb9-4107708911dc.png)
6.In Terminal/GitBash, type conda activate dev to activate a development environment
. Your Terminal/GitBash command prompt should now reflect the new environment (dev) tag:
![anaconda_activate_dev](https://user-images.githubusercontent.com/113739944/218256455-0a4cf9a4-b7b9-41aa-a470-616f9ad1c969.png)

7. To enable the Terminal/GitBash commands for conda:

Windows: All users type conda init bash.

Mac users running versions iOS 10.15 (Catalina) and later AND running the zsh terminal environment type conda init zsh.

Mac users running iOS versions earlier than 10.15 or running versions 10.15 with a bash terminal environment type conda init bash

Note: For Mac users that need to verify their iOS version, click on the Apple logo in the upper left hand corner of your screen and select "About this Mac". To verify if the shell you are using is bash or zsh, type echo #{SHELL}

8. You will need to install a dev environment kernel for eventual use with an interface called JupyterLab, which we will dive into in a few pages. To do this type python -m ipykernel install --user --name dev

9. You will also need to install a node environment to facilitate the interaction between your machine and JupyterLab, to do this type conda install -c conda-forge nodejs.

10. To exit your conda dev environment, type conda deactivate. The (dev) tag at the beginning of your command prompt line should not longer be reflected.

## Installation Guide
This does not require any installations or SDK's because we are using a web version of Remix IDE. 
---
## Usage
To use the Smart Contract Application simply clone the repository and in the terminal with:

```python
git clone ~ 'joint_savings.sol'
```

Upon launching the JointSavings Smart Contract Application  you will be greeted with the following prompts.

![20-1-remix-ide-first-launch](https://user-images.githubusercontent.com/113739944/218255962-7643672c-777b-4b01-8834-b2253287ce17.png)
 In the Featured Plugins area, we then click the Solidity button, as the image above shows:
![20-1-open-remix-file-browser](https://user-images.githubusercontent.com/113739944/218256015-bec81222-52cb-4680-bdc8-9f35d9603947.png)
click the “File explorers” button in the upper-left area of the window. Then click the button on the far right with the arrow pointing up out of the box. 



---
## Contributors
Brought to you by Marissa Gonzales.
## License
MIT
