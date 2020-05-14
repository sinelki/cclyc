# Comparison Class Learning in Young Children (CCLYC)

This repo contains all the software and data used in the MIT Master of Engineering thesis
[Comparison Class Learning in Young Children](http://library.mit.edu/F/PQKXE2YAGSC2MEUE92G1NESLJHRCHALE3ABDPS867K4HJBR97F-00503?func=file&amp=&amp=&amp=&amp=&amp=&amp=&file%5Fname=find-b&local%5Fbase=THESES2).

## Getting Started <a href=”getting-started”></a>
This repo uses submodules to provide a clean separation of each component. This allows each
component to be updated independently of each other.

To clone this repository and all submodules use the `--recurse-submodules` option:
```bash
git clone --recurse-submodules https://github.com/sinelki/cclyc.git
```

If you have already cloned the repository, you can update the submodules using the
`git submodule` command:
```bash
git submodule update *
```

## Project Structure <a href=”project-structure”></a>
The three submodules correspond to three distinct parts of the project:

[`providence_data_pipeline`](https://github.com/sinelki/providence_data_pipeline.git)
contains the database used to present utterances for annotations and the extracted dataset.

[`providence_annotation_backend`](https://github.com/sinelki/providence_annotation_backend.git)
contains the backend service that serves utterances from the database to the user for annotation.

[`providence_annotation_frontend`](https://github.com/sinelki/providence_annotation_frontend.git)
contains the frontend web page that presents the utterances to users.

More detailed information about each part of the project is described in the appropriate
submodule’s README.
