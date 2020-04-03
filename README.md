# VTKMinimal_jll.jl

This is an autogenerated package constructed using [`BinaryBuilder.jl`](https://github.com/JuliaPackaging/BinaryBuilder.jl).

## Products

The code bindings within this package are autogenerated from the following `Products` defined within the `build_tarballs.jl` file that generated this package:

```julia
products = [
    LibraryProduct(["libvtkFiltersSources"], :libvtkFiltersSources),
    LibraryProduct(["libvtkRenderingVolumeOpenGL2"], :libvtkRenderingVolumeOpenGL2),
    LibraryProduct(["libvtkFiltersHybrid"], :libvtkFiltersHybrid),
    LibraryProduct(["libvtkFiltersModeling"], :libvtkFiltersModeling),
    LibraryProduct(["libvtkFiltersParallelImaging"], :libvtkFiltersParallelImaging),
    LibraryProduct(["libvtkFiltersStatistics"], :libvtkFiltersStatistics),
    LibraryProduct(["libvtktheora"], :libvtktheora),
    LibraryProduct(["libvtkInteractionImage"], :libvtkInteractionImage),
    LibraryProduct(["libvtkParallelCore"], :libvtkParallelCore),
    LibraryProduct(["libvtkParallelDIY"], :libvtkParallelDIY),
    LibraryProduct(["libvtkFiltersSMP"], :libvtkFiltersSMP),
    LibraryProduct(["libvtkFiltersGeneric"], :libvtkFiltersGeneric),
    LibraryProduct(["libvtkFiltersImaging"], :libvtkFiltersImaging),
    LibraryProduct(["libvtkImagingHybrid"], :libvtkImagingHybrid),
    LibraryProduct(["libvtkFiltersSelection"], :libvtkFiltersSelection),
    LibraryProduct(["libvtkFiltersCore"], :libvtkFiltersCore),
    LibraryProduct(["libvtkRenderingContext2D"], :libvtkRenderingContext2D),
    LibraryProduct(["libvtkFiltersHyperTree"], :libvtkFiltersHyperTree),
    LibraryProduct(["libvtkCommonSystem"], :libvtkCommonSystem),
    LibraryProduct(["libvtkCommonExecutionModel"], :libvtkCommonExecutionModel),
    LibraryProduct(["libvtkIOImage"], :libvtkIOImage),
    LibraryProduct(["libvtkCommonColor"], :libvtkCommonColor),
    LibraryProduct(["libvtkFiltersParallel"], :libvtkFiltersParallel),
    LibraryProduct(["libvtksys"], :libvtksys),
    LibraryProduct(["libvtkRenderingContextOpenGL2"], :libvtkRenderingContextOpenGL2),
    LibraryProduct(["libvtkFiltersExtraction"], :libvtkFiltersExtraction),
    LibraryProduct(["libvtkRenderingCore"], :libvtkRenderingCore),
    LibraryProduct(["libvtkFiltersProgrammable"], :libvtkFiltersProgrammable),
    LibraryProduct(["libvtkImagingSources"], :libvtkImagingSources),
    LibraryProduct(["libvtkImagingColor"], :libvtkImagingColor),
    LibraryProduct(["libvtkCommonDataModel"], :libvtkCommonDataModel),
    LibraryProduct(["libvtkogg"], :libvtkogg),
    LibraryProduct(["libvtkFiltersGeneral"], :libvtkFiltersGeneral),
    LibraryProduct(["libvtkCommonComputationalGeometry"], :libvtkCommonComputationalGeometry),
    LibraryProduct(["libvtkViewsCore"], :libvtkViewsCore),
    LibraryProduct(["libvtkmetaio"], :libvtkmetaio),
    LibraryProduct(["libvtkInteractionWidgets"], :libvtkInteractionWidgets),
    LibraryProduct(["libvtkIOOggTheora"], :libvtkIOOggTheora),
    LibraryProduct(["libvtkIOMovie"], :libvtkIOMovie),
    LibraryProduct(["libvtkImagingCore"], :libvtkImagingCore),
    LibraryProduct(["libvtkCommonTransforms"], :libvtkCommonTransforms),
    LibraryProduct(["libvtkDICOMParser"], :libvtkDICOMParser),
    LibraryProduct(["libvtkImagingMorphological"], :libvtkImagingMorphological),
    LibraryProduct(["libvtkImagingMath"], :libvtkImagingMath),
    LibraryProduct(["libvtkCommonMath"], :libvtkCommonMath),
    LibraryProduct(["libvtkIOXMLParser"], :libvtkIOXMLParser),
    LibraryProduct(["libvtkIOLegacy"], :libvtkIOLegacy),
    LibraryProduct(["libvtkRenderingVolume"], :libvtkRenderingVolume),
    LibraryProduct(["libvtkImagingFourier"], :libvtkImagingFourier),
    LibraryProduct(["libvtkFiltersTexture"], :libvtkFiltersTexture),
    LibraryProduct(["libvtkFiltersFlowPaths"], :libvtkFiltersFlowPaths),
    LibraryProduct(["libvtkImagingStatistics"], :libvtkImagingStatistics),
    LibraryProduct(["libvtkFiltersPoints"], :libvtkFiltersPoints),
    LibraryProduct(["libvtkRenderingUI"], :libvtkRenderingUI),
    LibraryProduct(["libvtkpugixml"], :libvtkpugixml),
    LibraryProduct(["libvtkImagingGeneral"], :libvtkImagingGeneral),
    LibraryProduct(["libvtkCommonCore"], :libvtkCommonCore),
    LibraryProduct(["libvtkImagingStencil"], :libvtkImagingStencil),
    LibraryProduct(["libvtkRenderingLabel"], :libvtkRenderingLabel),
    LibraryProduct(["libvtkRenderingFreeType"], :libvtkRenderingFreeType),
    LibraryProduct(["libvtkInteractionStyle"], :libvtkInteractionStyle),
    LibraryProduct(["libvtkRenderingAnnotation"], :libvtkRenderingAnnotation),
    LibraryProduct(["libvtkdoubleconversion"], :libvtkdoubleconversion),
    LibraryProduct(["libvtkRenderingOpenGL2"], :libvtkRenderingOpenGL2),
    LibraryProduct(["libvtkCommonMisc"], :libvtkCommonMisc),
    LibraryProduct(["libvtkRenderingImage"], :libvtkRenderingImage),
    LibraryProduct(["libvtkIOXML"], :libvtkIOXML),
    LibraryProduct(["libvtkRenderingLOD"], :libvtkRenderingLOD),
    LibraryProduct(["libvtkIOCore"], :libvtkIOCore),
    LibraryProduct(["libvtkFiltersGeometry"], :libvtkFiltersGeometry),
    LibraryProduct(["libvtkFiltersTopology"], :libvtkFiltersTopology)
]
```

## Usage example

For example purposes, we will assume that the following products were defined in the imaginary package `Example_jll`:

```julia
products = [
    FileProduct("src/data.txt", :data_txt),
    LibraryProduct("libdataproc", :libdataproc),
    ExecutableProduct("mungify", :mungify_exe)
]
```

With such products defined, `Example_jll` would contain `data_txt`, `libdataproc` and `mungify_exe` symbols exported. For `FileProduct` variables, the exported value is a string pointing to the location of the file on-disk.  For `LibraryProduct` variables, it is a string corresponding to the `SONAME` of the desired library (it will have already been `dlopen()`'ed, so typical `ccall()` usage applies), and for `ExecutableProduct` variables, the exported value is a function that can be called to set appropriate environment variables.  Example:

```julia
using Example_jll

# For file products, you can access its file location directly:
data_lines = open(data_txt, "r") do io
    readlines(io)
end

# For library products, you can use the exported variable name in `ccall()` invocations directly
num_chars = ccall((:count_characters, libdataproc), Cint, (Cstring, Cint), data_lines[1], length(data_lines[1]))

# For executable products, you can use the exported variable name as a function that you can call
mungify_exe() do mungify_exe_path
    run(`$mungify_exe_path $num_chars`)
end
```
