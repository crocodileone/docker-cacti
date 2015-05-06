# docker-cacti

## Usage

Use the command below to run your own container:

    $ docker run -d -p 80 -p 161:161 leniy/cacti

## Accessing the Cacti applications:

Find your port by:

    $ docker ps

Then you can visit your site by the following url:

  - **http://host_ip:port/

Or access docker directly by:

  - **http://host_ip:port/cacti/

Then you can login by username:admin and password:admin.
