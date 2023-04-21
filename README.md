# Quake 3 Job for Racetrack

This is the source code of the Quake III job that runs on the [Racetrack](https://github.com/TheRacetrack/racetrack) framework.

The job simply serves static files using Racetrack's [webview feature](https://github.com/TheRacetrack/plugin-python-job-type/blob/master/docs/job_python3.md#custom-webview-ui-webview_app-method).
These files contain the Quake III Arena game ported to JavaScript which runs fully in your browser.

## Deploying to Racetrack

```sh
racetrack deploy quake3/job.yaml
```

and open this page in your browser `RACETRACK_ADDR/pub/job/quake3/0.0.1/api/v1/webview`.

## Based on

- [Quake III Arena JS - JavaScript porting](https://github.com/lrusso/Quake3)
- [QuakeJS](https://github.com/inolen/quakejs)
