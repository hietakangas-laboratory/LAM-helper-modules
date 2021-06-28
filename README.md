# LAM helper-modules
## Author: Jack Morikka

A set of small programs complementary to LAM functionality. Descriptions of each program below:


## imaris_to_lam

This is a program that uses .csv files saved from an IMARIS batch run and turns them into LAM ready folders.
Instructions:
* First select the IMARIS batch save output that should be a directory named e.g. 'Spots_1_Statistics'
* Then select the output folder
* Finally input a name for this 'spot' e.g. DAPI,GFP or MP.

**N.B.** this program requires that the tiffs processed in IMARIS were named in the format: NAME_YYYY-MM-DD_XXXXXX.

* Once finished with 'Spots_1_Statistics', repeat for 'Spots_2_Statistics' making sure to choose the same output folder.
* Repeat for as many spots as you want to compare.

# manual_vec_sorter

This is a small program that takes tiffs with manual 'vectors' drawn in imageJ and saves all 
the vectors as vector.txt files and then moves them into the correct LAM files in a LAM analysis samples folder.
As in the IMARIS_to_LAM programme, this programme requires that your tiffs are named in 
the format: NAME_YYYY-MM-DD_XXXXXX. 

Instructions:

* Select the imageJ.exe file (usually somewhere like: "C:\hyapp\fiji-win64-1.52p\Fiji.app\ImageJ-win64.exe")
* Then select the input folder with the tiffs containing the manually drawn vectors (make sure that is all this folder contains).
* Finally select the LAM /analysis/samples folder with the samples corresponding to the tiffs. **N.B.** the sample folders must
have the same name as the tiffs e.g. 'OR_2020-08-31_145800' so that the programme can move the vector files to the correct folder.

# mp_sorter

This is a small program that takes tiffs with manual 'MPs' drawn in imageJ and saves all 
these MPs in the into the correct LAM files in a LAM analysis samples folder.
As in the IMARIS_to_LAM programme, this programme requires that your tiffs are named in 
the format: NAME_YYYY-MM-DD_XXXXXX. 

Instructions:

* Select the imageJ.exe file (usually somewhere like: "C:\hyapp\fiji-win64-1.52p\Fiji.app\ImageJ-win64.exe")
* Then select the input folder with the tiffs containing the manually drawn MPs(make sure that is all this folder contains).
* Finally select the root folder which you will use for a lam analysis, with folders containing data relevant to each of the samples corresponding to the tiffs. **N.B.** the sample folders must
have the same name as the tiffs e.g. 'OR_2020-08-31_145800' so that the programme can move the vector files to the correct folder.

