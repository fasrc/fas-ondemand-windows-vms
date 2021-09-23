# Windows VMs on FAS-OnDemand 

This app was adapted from original code kindly provided by PURDUE University.

This app will launch a Windows VM running as batch job in our FAS-OnDemand slurm cluster.

## Dependencies.

... WIP ...

## Use

The master branch of this repository is used as template to generate customized version of the app for different academic courses on FAS-OnDemand requiring different base images to support a number of different applications.
The actual apps deployed on the cluster are stored in [this repository](https://github.com/fasrc/fas-ondemand-windows-vms-apps).

If you want to deploy this repo in your user development environment to make modifications, follow these instructions. 

```sh
# create the development folder if you still not have one
mkdir -pv $HOME/.fasrc/dev/
cd $HOME/.fasrc/dev/

# clone the repository in a subfolder for your version of the app
git clone https://github.com/fasrc/fas-ondemand-windows-vms.git

# Change the working directory to this new directory
cd fas-ondemand-windows-vms
```
You can now make your preferred modifications and run your version of the app from the sandbox control panel under the
*dev* menu on the ondemand dashboard

## Contributing

If you intend deploy your modified version as system wide app, please commit your changes to a branch first, and open a PR.
