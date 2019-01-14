Docker Image for Booked Scheduler
===

## Installation

1. Download or clone the files in this repo `git clone https://github.com/khal3d/docker-booked.git`
2. Edit the following config in the config.php file
```
$conf['settings']['script.url'] = 'http://localhost/Web';
$conf['settings']['database']['user'] = 'booked_user';
$conf['settings']['database']['password'] = 'password';
$conf['settings']['install.password'] = ''; // Add random password for the installation
```
3. Run the following command to run the docker images `docker-compose up -d`
4. Go to the URL `http://localhost:8009/Web/install/` to complete the installation setup
