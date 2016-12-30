[![Project Status](http://opensource.box.com/badges/active.svg)](http://opensource.box.com/badges)

Adding Attribute Support to out-of-box Sales Order Entity
==================================
An extension that allows to add attribute support to out-of-box Sales Order Entity.

###Prerequisites
* Acumatica 6.0 or higher

Quick Start
-----------

### Installation

##### Install the customization deployment package
1. Download PXSOAttributeSupportExtPkg.zip from this repository
2. In your Acumatica ERP instance, navigate to System -> Customization -> Customization Projects (SM204505), import PXSOAttributeSupportExtPkg.zip as a customization project
3. Publish the customization project.

### Configuration

1. Go to Attributes Screen (CS205000) and create new attributes if you need to.
2. Navigate to Order Types Screen (SO201000) and select the Order Type for which you need to specify list of Attributes, a new Attribute Tab is available to include attributes.
![Screenshot](/_ReadMeImages/SO201000.png)
3. Navigate to Sales Orders Screen (SO301000) and select the Order Type for which you have specified the Attributes in Step # 2, you should be able to see Attributes specified in Step # 2 and can specify value for them.
![Screenshot](/_ReadMeImages/SO301000.png)
