# ProcessorPackingSupports

A collection of 3d printable packing supports for processors.

## Processors by Socket

- [AM4](AM4/README.md)

## Contribution Guide

This project aims to create 3D packing designs under the GPL V2 License. Commercial entities are encouraged to use the
designs in packaging and contribute improvements and/or other processor models.

Models will be organized by their socket-type (such as AM4) and categorized further into the shipping vendor for the
packaging material (say USPS). For designs around generic box sizes they will be stored in a 'Generic' folder. All
3rd party designs used in the project will be placed in a 'Common' folder under the socket folder.

README docs will be author'd for each packaging design. When possible images of the box should be stored under an 'img'
directory with the stl for reference in README files.

Example structure:

- AM4
  - Common
    - CPU trays used by other designs
  - USPS
    - Small flat rate box
      - README.md
      - AM4_USPS_FLAT_RATE_SMALL_BOX.stl
      - img
        - USPS_FLAT_RATE_SMALL_BOX.png
    - Large flat rate box
      - ...
  - FEDEX
    - FedExExpressSmallBox
      - README.md
      - AM4_FedEx_Express_Small_Box.stl

## 3rd party designs used in this project

This project makes use of existing CPU trays make by other designers. Users and contributors of this project must
adhere to licenses of other assets such as the
[BritsFabrication AM4 CPU Tray](AM4/Common/BritsFabrication-am4-amd-cpu-tray-box/README.md).
