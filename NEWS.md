flowr: 0.96.1
----------------------------------------------




flowr: 0.95.1
----------------------------------------------

- Added several new functions kill_flow(), which kills the flow.
- Added experimental rerun_flow which still needs some work
- Added some vignettes for a simple and comples example
- updated documentation to satiate R CMD check
- now job() checks for a dependency_type is previous job is provided
- Added some slides inst
- Integrated documentation with Sphnix
- submit_flow, now generates flow_details.txt, flow.pdf,
flow_status.txt
- status() updates: flow_details.txt and flow_status.txt
- save flow.rda files with all details on the flow
- update flow details with job exit status, to be used in rerun
- Now flow_status, reports started, completed, exited.

### TODO:
- add more examples
- update and cleanup documentation
- integrate with sqlite with status
- add example pipelines
- assign UUID to each job/flow. and use that to track them.
- Work on test_queue()
- Add recipies

flow: 0.85
----------------------------------------------

## todo:
  - get\_flow_details():
    Attach a job_number
  Attach a flow level unique ID
  - update flow details with exited jobs
  - Create trigger upon start
  - add started/pending column in details and summary

### plot_flow():
  make plot type 1 as default
### get_flow_status():
  exit_status: reports number of exited jobs (not sum of exit codes)