# plant_image_processing
Rename batch files and measure growth of each plant. Plants are grown in agar in tissue culture plates. Pictures taken of each well individually on a lightbox, with camera at a set height for consistancy. This minimizes the need to do fish-eye corrections used in other scripts.


# Re-naming Files
When renaming a batch of files, need to provide a csv file with the column header "new_names". The column should contain a list of the new file names.

The script counts the number of new names listed as well as the number of files to rename. If the numbers are not the same, the script stops running. 
