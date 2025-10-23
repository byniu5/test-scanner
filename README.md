# test-scanner


## For Docker
```
# -------------SET URL FOR SCAN-------------
docker run --rm `
   -v ${PWD}:/dastardly `
   -e DASTARDLY_TARGET_URL= `
   -e DASTARDLY_OUTPUT_FILE=/dastardly/dastardly-report.xml `
   public.ecr.aws/portswigger/dastardly:latest
```
