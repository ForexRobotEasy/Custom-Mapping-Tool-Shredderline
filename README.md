# Shredderline Custom Mapping Tool

## Description
Shredderline is a custom mapping tool designed to simplify forex charting. It is developed by the Forex Robot Easy Team and can be used as a standalone indicator in MetaTrader 4.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/shredderline-custom-mapping-tool-review-simplify-forex-charting/).

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Features
- Draws a path on the chart
- Allows cropping desired areas of the chart

## Indicator Properties
- Chart window: Enabled
- Number of buffers: 1
- Number of plots: 2
- Color of plot 1: SteelBlue
- Color of plot 2: Tomato
- Width of plot 1: 2
- Width of plot 2: 2

## Buffer Arrays
- DrawPathBuffer: Stores data for drawing the path on the chart
- CropBuffer: Stores data for cropping desired areas of the chart

## Initialization
- Sets buffer arrays for drawing and cropping
- Sets indicator labels for the plots
- Sets indicator styles for the plots
- Sets indicator colors for the plots
- Checks if Crop function is enabled and displays the crop button in the Drawing menu panel

## Functions
- `IsOptionEnabled(int option)`: Checks if the Crop function is enabled
- `DisplayCropButton()`: Displays the crop button in the Drawing menu panel
- `CropChart()`: Crops desired areas of the chart (to be implemented)

Please note that the `CropChart()` function is not implemented in this code. It is mentioned as a placeholder for future implementation.

For more information and usage instructions, please refer to the official documentation or contact the official developer of this product through MQL5.
