# HRRR-io

These notebooks represent a non-specialist interacting with the HRRR data located on the AWS registry: https://registry.opendata.aws/noaa-hrrr-pds/. I got help from the numerous tutorials online and [Joseph Kennedy](https://github.com/jhkennedy). In fact, much of the content is literally taking the examples online and running through them with lots of commentary.

There are two formats (1) `grib2` and (2) `zarr`. The first two notebooks touch on each, respectively. The `grib2` files are more carefully investigated because they cover the full model record. The last notebook uses [Herbie](https://github.com/blaylockbk/Herbie/tree/main/herbie) to download `grib2` files.

I had some issues with `fsspec` and `herbie` so I separated the environments. The kernel names should match the environments `xarray` and `herbie`, respectively.