# Firma 🌍

A Python equivalent of the R Terra package for spatial data science, for both raster and vector data.

⚙️ **Firma is a work in progress, and is not yet ready for use.** ⚒️

## Why

As an R native, I have found that working with spatial data in Python is very fragmented and tedious, involving lots of packages for different file types. Compare this to [R Terra](https://github.com/rspatial/terra), which can handle almost any geospatial file format for both vector and raster data, enabling you to do almost anything with your data.

I have therefore decided to create a Python equivalent of the Terra package, which I have named Firma (because Terra Firma haha).

## Firma Goals

The main goals of Firma are:

* To provide a single, easy to use package for all spatial raster and vector data science tasks.
* Maximal file format support, including GeoTIFF, NetCDF, HDF, GRIB, and more.
* Minimal barrier to entry for users transferring from R Terra.
* To be as fast as possible and parallelize as much as possible.
