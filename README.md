 #Check out solution URL
$ cat solution.txt
Georgousis911.github.io
# Ensure the URL exists
$ curl --output /dev/null --silent --head --fail Georgousis.github.io && \
echo "URL exists" || echo "URL does not exist"
URL exists
https://github.com/Georgousis911/progintro-hw0--Georgousis911-
