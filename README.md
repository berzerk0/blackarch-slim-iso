# BlackArch Slim ISO
## A Live-Boot-Friendly BlackArch ISO with a streamlined package list.

***

## Files

__build.sh__
- Image creation script.

__packages.x86_64__
- Default packages installed on the Slim ISO.

__airootfs/root/customize_airootfs.sh__
- Executes commands on the Slim ISO during the building process. Modify this file to run a
 administrative command or alter a configuration file.



### Building the Image

Clone this repository, then run the following commands:

```
cd blackarch-slim-iso
rm -rfv out work
mkdir out work
./build.sh -v
```

The finished ISO will be located in the `out` folder.

### Screenshots

![empty](docs/empty.png)
![fakebusy](docs/fakebusy.png)
![another fakebusy](docs/fakebusy1.png)

### Suggestions

*Have an idea to improve the Slim ISO?*
- Please consider opening a New Issue!
- Include a detailed description to ensure an effective, informative issue.

*Would you like to see an application included in Slim ISO?*
- Create an Issue or Pull Request
- Write a detailed description outlining why the application should be included.
