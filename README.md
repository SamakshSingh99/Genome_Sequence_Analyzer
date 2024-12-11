# GeneScoPy
Genome assembly sequence and GFF/GTF file analyzer

## Overview
GeneScoPy is a standalone graphical user interface (GUI) tool for working with genome assembly sequence files (FASTA) and genome annotation files (GTF/GFF). It provides a platform for:

- Inspecting and managing genome assembly files.
- Viewing genome annotation details.
- Performing basic analyses such as computing assembly statistics (e.g., N50, GC content, scaffold sizes).
- Searching and navigating annotation files efficiently.

## Key Features
- **File Compatibility**: Supports FASTA and GTF/GFF file formats.
- **Assembly Details**: Displays total assembly length, scaffold counts, largest and smallest scaffolds, N50, and GC content.
- **Annotation Table**: Presents GTF/GFF data in an easy-to-navigate table with fields like scaffold, source, feature, start and end positions, strand, frame, product, and gene name.
- **Sequence Viewer**: Allows users to view scaffold sequences in a text editor.
- **Search Functionality**: Provides tools for searching and navigating annotation records by keywords.
- **User-Friendly Interface**: Built with a modern and intuitive GUI.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/SamakshSingh99/GeneScoPy/
   cd GeneScoPy
   ```
2. Ensure you have Python installed (version 3.7 or higher).
3. Install required dependencies:
   ```bash
   pip install tk
   ```
4. Run the tool:
   ```bash
   python ./Script/Script.py
   ```

## How to Use
### Opening Files
1. Launch the application.
2. Use the `File` menu to open a FASTA file or GTF/GFF file.

### Viewing Assembly Details
- After loading a FASTA file, the "Assembly Details" section will display information about:
  - Total assembly length.
  - Number of scaffolds.
  - Largest and smallest scaffolds.
  - N50 value.

### Viewing Annotation Data
- Load a GTF/GFF file to populate the annotation table.
- Use the table columns to explore scaffold details, gene annotations, and other metadata.

### Searching Annotations
- Use the search bar to find specific entries in the annotation table.
- Navigate through results using the `Previous` and `Next` buttons.
- Reset the search to view the entire table again.

## File Management
- Scaffold sequences can be selected from the list and displayed in the sequence viewer for detailed inspection.

## Contributing
Contributions are welcome! If you'd like to enhance the tool or fix any bugs:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to the bioinformatics community for inspiring this project.

## Contact
For questions or support, please open an issue on the GitHub repository.
