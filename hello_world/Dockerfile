# Pulling the latest mono image from the docker hub
FROM mono:latest

# Adding the src folder to the home directory
ADD . /home/nishant/helloWorld

# Compile the helloWorld.cs file and generates a helloWorld.exe
RUN mcs /home/nishant/helloWorld/helloWorld.cs

# Executing the helloWorld.exe
CMD [ "mono", "/home/nishant/helloWorld/helloWorld.exe" ]