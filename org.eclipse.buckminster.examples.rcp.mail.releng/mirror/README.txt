You can run the mirror.ant file to get a local mirror of the
repositories used for our target platform.

You can run the ant file from the command line, by using one of your
eclipse installation

/path/to/eclipse -noSplash \
   -application org.eclipse.ant.core.antRunner \
   -buildfile mirror.ant \
   -Dtarget.dir=$HOME/eclipsemirror

or use the run_mirror.launch configuration from the
Eclipse IDE (make sure to run it from a workspace using
the running platform, since org.apache.ant is required).

see also these blog posts

http://www.lorenzobettini.it/2012/11/mirror-eclipse-repositories-with-p2-mirror-ant-task/
http://www.lorenzobettini.it/2012/12/mirror-eclipse-repositories-from-eclipse/

