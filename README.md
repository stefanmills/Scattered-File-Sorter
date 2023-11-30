# Scattered-File-Sorter
Certainly! Here's a basic README for your scattered file sorter:

---

# Scattered File Sorter for Data Analysts

This Python script is designed to assist data analysts in sorting scattered files into folders based on their file extensions. Instead of manually organizing files, this tool automates the process, saving time and ensuring a more organized file structure.

## Usage

1. **Run the Script:**
   - Execute the script by providing the path to the folder containing scattered files.
   - If needed, replace the predefined path in the script.

   ```bash
   python file_sorter.py
   ```

2. **Input Path:**
   - When prompted, enter the path to the folder containing scattered files.

3. **Sorting Process:**
   - The script will create folders for each unique file extension and move corresponding files into their respective folders.

4. **Completion Message:**
   - Once the sorting is complete, a message will be displayed.

## Estimated Run Time

The run time of the script depends on the number of files and their sizes. Generally, for a moderate number of files, the process should be relatively quick. However, for a large number of files, the execution time may increase.

## Notes

- The script uses the `shutil` library to move files, so be cautious when using it on valuable or irreplaceable data.
- Double-check the results to ensure files are correctly sorted.

---

Feel free to customize this README based on additional features or considerations specific to your script. Additionally, if you have any performance optimizations, you can provide guidance on how to handle larger datasets more efficiently.
