# How to reset ASP.NET MVC PivotGrid to initial state while enabling EnablePersistence

## Project Overview

This sample application showcases how to implement a reset functionality for PivotGrid controls without disabling the persistence feature. PivotGrid persistence allows users' configurations to be retained across sessions, but sometimes applications need to provide users with a way to clear all customizations and return to the default state. This project addresses that requirement by demonstrating the proper approach to achieve this functionality.

## Features

* **PivotGrid Reset Capability** - Clear all user customizations while keeping EnablePersistence active
* **EssentialJS2 Integration** - Utilizes Syncfusion EssentialJS2 components for advanced PivotGrid functionality
* **ASP.NET MVC Architecture** - Built on the ASP.NET MVC framework with C# backend
* **State Management** - Demonstrates proper state handling and configuration management
* **User-Friendly Interface** - Provides intuitive controls for resetting to initial state

## Prerequisites

* Visual Studio 2022
* .NET Framework 4.7.2 or higher
* Syncfusion EssentialJS2 NuGet packages
* NuGet Package Manager for dependency restoration

## Installation & Setup

1. **Checkout the project** - Clone or download this project to a location on your disk
2. **Open the solution** - Launch the `.sln` file using Visual Studio 2022
3. **Restore NuGet packages** - Rebuild the solution to restore all required dependencies
4. **Build the project** - Ensure all packages are properly installed without errors
5. **Run the application** - Start the application to view the PivotGrid in action

## Usage

1. Navigate to the PivotGrid Features page in the application
2. Interact with the PivotGrid by customizing fields, filters, and layout
3. Observe how the EnablePersistence feature retains your changes
4. Click the Reset button to return the PivotGrid to its initial state
5. Verify that persistence is still active for future customizations

## Configuration

The PivotGrid is configured with EnablePersistence to automatically save user preferences. The reset functionality works by clearing the persisted state while maintaining the EnablePersistence setting, allowing users to start fresh while keeping the feature available for subsequent uses.

## Support & Resources

For additional information on Syncfusion EssentialJS2 PivotGrid controls, refer to the official documentation and Syncfusion knowledge base. This implementation follows best practices for managing component state in ASP.NET MVC applications.