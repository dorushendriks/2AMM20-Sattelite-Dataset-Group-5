# Sattelite-Dataset

Contains modified Copernicus Sentinel-2 data 2024, processed by Group 5 of the Neural fields trajectory for the course 
Research Topics in Data Mining at TU/e.

See https://sentiwiki.copernicus.eu/web/s2-mission

The data is modified by converting it to 13 x 1024 x 1024 numpy matrices, 
representing a 1024 x 1024 images and the 13 different wavelengths.
It is used for the purpose of testing compression methods for highly dimensional imagery.


# Acknowledgements
The data is provided under the terms and conditions of the Legal Notice on the use of Copernicus Sentinel Data (https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice).

# Overview
An overview of all images is given below, the sentinel 2 ID can be used
to retrieve both the date and location of the image.


ijsselmeer-and-surroundings-low-clouds-relatively-dark

    S2B_MSIL1C_20231017T104939_N0509_R051_T31UFU_20231017T125432.SAFE

sahara-desert-south-algeria-low-clouds

    S2B_MSIL1C_20231018T101939_N0509_R065_T31REH_20231018T140012.SAFE

amazon-rainforest-minor-clouds

    S2B_MSIL1C_20230927T142719_N0509_R053_T20MPD_20230927T174905.SAFE

great-barrier-reef-low-clouds

    S2B_MSIL1C_20241003T001109_N0511_R073_T56KKC_20241003T025213.SAFE

bahamas-during-hurricane-doraine

    S2B_MSIL1C_20190902T154549_N0208_R111_T18QVM_20190902T203822.SAFE

tokyo-low-clouds

    S2B_MSIL1C_20240705T012659_N0510_R074_T54SUE_20240705T024824.SAFE

alps-spring

    S2A_MSIL2A_20230406T102021_N0509_R065_T32TNS_20230406T194357.SAFE

bejing-lowclouds

    S2A_MSIL2A_20230914T030531_N0509_R075_T50TMK_20230914T083003.SAFE

us-suburban-sprawl

	S2A_MSIL2A_20241012T161221_N0511_R140_T17RLQ_20241012T222848.SAFE

congo-deforestation

    S2B_MSIL2A_20241011T090819_N0511_R050_T33NVA_20241011T122228.SAFE

wildfires-US-yosemite-2018

    S2B_MSIL2A_20180726T184029_N0500_R070_T11SKB_20230722T011822.SAFE

melting-coastal-ice

    S2A_MSIL2A_20240920T171011_N0511_R112_T16VEM_20240920T232257.SAFE

#