Build the Docker image:

Open a terminal, navigate to the directory containing your Dockerfile and generate_report.py, and run the following command
docker build -t report-generator .

Run the Docker container:

To run the container and generate the report, use the following command:
docker run --rm -v $(pwd)/reports:/app report-generator
