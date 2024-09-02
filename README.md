# ImageToPDFConverter

## Description
`ImageToPDFConverter` is a Python GUI application that allows users to convert multiple image files (such as PNG, JPG, etc.) into a single PDF document. The application features real-time progress tracking and options to clear tasks or open the generated PDF file or its containing directory directly from the application.

## Features
- Supports multiple image formats (PNG, JPG, etc.)
- Real-time progress tracking during PDF generation
- Option to clear tasks and start a new conversion process
- Easily open the generated PDF file or its containing directory

## Requirements
- Python 3.6+
- `Pillow` for image handling
- `reportlab` for PDF generation
- `tkinter` for GUI

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ImageToPDFConverter.git
    cd ImageToPDFConverter
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the application:
    ```bash
    python image_to_pdf.py
    ```
2. Click "Browse Files" to select the images you want to convert to PDF.
3. Choose the save location for the output PDF file.
4. Watch the real-time progress as the PDF is generated.
5. Optionally, open the PDF or its directory directly from the application.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
