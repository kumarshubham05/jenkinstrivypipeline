# Trivy Scanner

Trivy is an open-source and simple and comprehensive vulnerability Scanner for containers and other artefacts. Trivy was developed in the year 2019 by Aqua Security. It detects vulnerabilities of OS packages and also application dependencies. Before pushing to a container registry or deploying your application, you can scan your local container image and other artefacts easily. Hence, this gives you the confidence that all is well with your application without more stressful configurations to use like other scanners.

## Quick Start
**1. Scanning any image from Dockerhub.**

Step 1: Select "Docker_Image_Name" option from CMD_INPUT drop down menu. <br />
Step 2: Enter the name of Docker image along with tag. If tag is not provided, it will pull the latest tagged image from dockerhub. <br />
Step 3: Click on build. <br />
Step 4: Once the build is complete, Click on Trivy-Scanner on top left and select "HTML Report" option to display the report. <br />

**2. Scan an image by uploading the Dockerfile.**

Step 1: Select "Dockerfile" option from CMD_INPUT drop down menu. <br />
Step 2: Enter the name of the docker image that you wnat to give and click on build. <br />
Step 3: On pipeline step, the build will get pause for you to upload your Dockerfile. Upload the Dockerfile and click on proceed. <br />
Step 4: Once the build is complete, Click on Trivy-Scanner on top left and select "HTML Report" option to display the report. <br />

**3. Scan an image by giving the github URL.**

Step 1: Select "Git_Rep_URL" option from CMD_INPUT drop down menu. <br />
Step 2: Enter the URL of the Github in the space provided. <br />
Step 3: Click on Build. <br />
Step 4: Once the build is complete, Click on Trivy-Scanner on top left and select "HTML Report" option to display the report. <br />