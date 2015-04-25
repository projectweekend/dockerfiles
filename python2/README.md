# Details

* Default `ENTRYPOINT` is `python`.
* Copies `requirements.txt` file into `/src` and installs dependencies.
* Has `ipython` installed.


### Launch ipython

```
docker run -it -v ${PWD}:/src --entrypoint=ipython name_of_image
```
