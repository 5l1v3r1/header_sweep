# header_sweep
This is a small python command-line tool for auditing a web application's HTTP security headers and secure cookie configurations.

### Installation :
Assuming python and pip are available and on global path (you can always use virtualenv to install the dependencies on an isolated instance) :

<code> make install </code>

### Usage :
(try -h for details)

<code> python header_sweep.py -t [http[s]://target.url/target.uri] -o [output_file]
       --no-cert : Turn off TLS certificate validation
       --auth=username:password : Use basic auth credentials
</code>
