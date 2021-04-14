# deepracer-log-analysis
## *Adventures in a data-driven approach to training, evaluating and tuning AWS DeepRacer reinforcement learning models.*

<br>

This Notebook, which is compatible with logs from the AWS DeepRacer Console after Aug 2020, is a redo of Log Analysis solutions provided in the [AWS DeepRacer Workshops repository](https://github.com/aws-samples/aws-deepracer-workshops). The log analysis here parses log data from AWS RoboMaker (SIM_TRACE_LOG data) and Amazon SageMaker (policy training data), and added some analysis.

The logs can be downloaded from AWS DeepRacer console after training has finished or terminated.

## How to use?

To take this Notebook on a quick test drive, just do the following:
- Clone this repo
- Download your own model training log (.tar.gz file) from the AWS DeepRacer console
- Extract the RoboMaker and SageMaker log files (found in `logs/training/` in the .tar.gz), into the `logs` folder
- Spin the .ipynb file up on Jupyter Notebook (works in an Amazon SageMaker Notebook instance too)
- Edit the path to your logs in the Notebook
- Run all cells to test the log analysis on your logs!

## Credits

Credits to:
- The AWS DeepRacer product and data science teams who had shared the original Log Analysis code as part of the AWS DeepRacer Workshops repository.
- AWS DeepRacer Community members who have shared ideas and contributed in one way or another.

## License

This project retains the license of the aws-deepracer-workshops project from which this was based. Our understanding is that it is a license more permissive than the MIT license and allows for removing of the copyright headers.

Unless explicitly sated otherwise, this license applies to all files in this repository.
