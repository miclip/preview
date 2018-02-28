# preview
dotnet core 2.1 preview 

~~~
dotnet publish -f netcoreapp2.1 -r ubuntu.14.04-x64
~~~

~~~
cf push preview -p bin/Debug/netcoreapp2.1/ubuntu.14.04-x64/publish/ -b dotnet_core_buildpack
~~~
