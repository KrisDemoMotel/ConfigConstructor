# Config Construction

An example on how to construct configuration files from an arbitrary list of jobs and workflows, laid out into files.

## How to Use

To try this out, you are welcome to add logic into `.circleci/config.yml` to determine what file to load and when. Ensure that Jobs and Workflows are kept in their own files,
and that they follow the proper formatting.

When running, the configuration will insert first the Jobs, then the Workflows into the appropriate spots. Once done, it will load the final, completed configuration. In this case, there is only "common", but it can easily be expanded to have more.