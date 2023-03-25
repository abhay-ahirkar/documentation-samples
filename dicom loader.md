# DICOM Loader for InVesalius

The DICOM Loader for InVesalius is a Python tool that allows users to search for and load DICOM images from a PACS server into InVesalius for processing. The tool is developed using Python and wxPython, and the Orthanc PACS server and REST API are used for storing and retrieving DICOM images.

## Installation

To install the DICOM Loader for InVesalius, follow these steps:

1.  Clone this repository to your local machine.
2.  Install the required packages by running `pip install -r requirements.txt`.
3.  Run the `dicom_loader.py` file to launch the GUI.

## Usage

Once the GUI is launched, follow these steps to use the DICOM Loader for InVesalius:

1.  Click on the "Connect to PACS" button to connect to the Orthanc PACS server.
2.  Use the search fields to search for DICOM images by patient name, ID, or date range.
3.  Select the desired images from the search results and click "Load" to load them into InVesalius.
4.  Once the images are loaded into InVesalius, use the software's tools to process the images as desired.
5.  To save surfaces and masks to the PACS server, select the "Save to PACS" option from the "File" menu.

## Contributing

Contributions to the DICOM Loader for InVesalius project are welcome! To contribute, follow these steps:

1.  Fork this repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and test them thoroughly.
4.  Submit a pull request with a detailed description of your changes.

## Credits

The DICOM Loader for InVesalius was developed by Abhay Ahirkar as part of 'Add PACS Communication'. The tool was developed using Python and wxPython, and the Orthanc PACS server and REST API were used for storing and retrieving DICOM images.

## License

The DICOM Loader for InVesalius is released under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for more information.
