# Angular lib workflow

> This is an experimental pipeline for Angular libraries continuous integration and delivery.
>
> Whenever a pull request is made over *main* branch, the pipeline is invoked and some checks are verified.
>
> First, compilation problems are checked, then coding styles are verified, as well as vulnerabilities and potential bugs.
>
> At last, tests are executed and coverage is verified.
>
> If everthing is in order, this workflow updates library version and creates a tag for a release candidate.
>
> If a release is performed, this pipeline publishes the library in github npm.

