---
title: PDF Document Conversion via Java 
url: /java/conversion/
description: Convert PDF to Microsoft Excel Word PowerPoint Slides, HTML, Images and many other popular formats with just few lines of Java code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PDF File Conversion via Java" h2="Export PDF to Microsoft Office® Word, Excel, PowerPoint Presentations, HTML, Images and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
When your solution does not support PDF manipulation inside the application and there is need to convert whole PDF data into other formats. **Java PDF library** is there to support your application. Enhancing application for PDF conversion functionality to manipulate data as of supported formats is easy and simple. To **convert PDF to Excel**, Word, HTML, Images or any required format, Few **Java PDF converter** code snippets, We are discussing here so that programmers can modify these conversion codes as of their requirements. Developers can easily automates conversion processes using these codes.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to Microsoft Word DOCX / DOC Formats" %}}
PDF Parser Java library supports all PDF to Microsoft<sup>&reg;</sup> Word format conversions. In case we are just converting Microsoft Word documents without any special settings, Then after loading the PDF file using [Document class](https://apireference.aspose.com/pdf/java/com.aspose.pdf/document), library's Save method will used with output Word document path and [SaveFormat](https://apireference.aspose.com/pdf/java/com.aspose.pdf/saveformat) as parameters.  For the special cases where there is need more settings before conversion, API has [DocSaveOptions class](https://apireference.aspose.com/java/pdf/com.aspose.pdf/DocSaveOptions) class that exposes all such settings. 
{{% blocks/products/pf/feature-page-code h3="Java PDF to Word Converter Code" %}}

```cs
// Load source PDF file
Document srcFile = new Document("input.pdf");

// Intialize DocSaveOptions Object
DocSaveOptions svopt = new DocSaveOptions();

// Set output format
svopt.setFormat(DocSaveOptions.DocFormat.DocX);

// Set the recognition mode as Flow
svopt.setMode(DocSaveOptions.RecognitionMode.Flow);

// Setting the horizontal proximity as 2.5
svopt.setRelativeHorizontalProximity(2.5f);

// Enable bullets recognition 
svopt.setRecognizeBullets(true);

// Save into Microsoft Word file
srcFile.save("pdf-to-word.docx", svopt);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-doc pdf-to-docx" >}}


{{% blocks/products/pf/feature-page-section  h2="PDF to Excel Conversion" %}}
Specialized [SaveFormat.Excel](https://apireference.aspose.com/pdf/java/com.aspose.pdf/SaveFormat#Excel) Enumeration available for saving PDF to Excel XLSX XLS output formats. Moreover, **Java PDF Library** also have a speicific [ExcelSaveOptions class](https://apireference.aspose.com/pdf/java/com.aspose.pdf/ExcelSaveOptions) that not only deals saving to Excel formats but also provides different functions and properties for setting different attributes like exact output format, minimize number of worksheets and more.
 
{{% blocks/products/pf/feature-page-code h3="Java PDF to Excel Example Code" %}}

```cs
// Load source PDF file
Document pdftoxlsx = new Document("srouceFile.pdf");
// Set Excel options
ExcelSaveOptions opts = new ExcelSaveOptions();
// Set output format
opts.setFormat(ExcelSaveOptions.ExcelFormat.XLSX);
// Set minimizing option
opts.setMinimizeTheNumberOfWorksheets(true);
// Convert PDF to Excel
pdftoxlsx.save("pdf-to-excel.xlsx", opts);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-xls pdf-to-xlsx" >}}

{{% blocks/products/pf/feature-page-section  h2="Save PDF File to PowerPoint Presentations" %}}
Java PDF API supports converting PDF pages to PowerPoint Presentation Slides by rendering slides as images. Pattern of saving PDF to PowerPoint PPTX / PPT is almost same, Loading the file using Document class and then calling the Save method with output file path and SaveFormat as parameters. In case of rendering with special presentation options, Programmers can use [PptxSaveOptions class](https://apireference.aspose.com/pdf/java/com.aspose.pdf/PptxSaveOptions) with any relevant specific rendering options. Calling the save method and passing the options as parameter.
{{% blocks/products/pf/feature-page-code h3="PDF to PowerPoint Slides Conversion Java Code" %}}
```cs
// Load PDF document
Document pdfFile = new Document("sourceFile.pdf");
// Set Microsoft PowerPoint PPTX save options
PptxSaveOptions pptxSettingOpt = new PptxSaveOptions();
pptxSettingOpt.setSlidesAsImages(true);
// Save PDF as PowerPoint PPTX Presentation
pdfFile.save("pdf-to-powerpoint.pptx", pptxSettingOpt);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Save PDF to HyperText Markup Language HTML" %}}
PDF Parser Library supports PDF to HTML conversion as whole as well as with embedded resources including images. Conversion process is same as PDF to other formats in general, like getting the source file and calling the Save method with output HTML file path and SaveFormat.Html as parameters. In case of saving with embedded resources, there is a [HtmlSaveOptions class](https://apireference.aspose.com/pdf/java/com.aspose.pdf/htmlsaveoptions) having multiple options like saving images to a specific folder during the conversion, layers rendering, transparent text rendering, splitting the resultant HTML into multiple pages, create subsequent documents with body contents only and more. 
{{% blocks/products/pf/feature-page-code h3="PDF to HTML Converter Java Code" %}}

```cs
// Load PDF document
Document pdfSourceFile = new Document("srcFile.pdf");

// Instantiate HTML SaveOptions object
HtmlSaveOptions savingOptions = new HtmlSaveOptions();

savingOptions.HtmlMarkupGenerationMode = HtmlSaveOptions.HtmlMarkupGenerationModes.WriteOnlyBodyContent;

// Specify to split the output into multiple pages
savingOptions.setSplitIntoPages(true);

// Specify the separate folder to save images
savingOptions.SpecialFolderForAllImages = "ImagesFolder";

// savingOptions.SaveShadowedTextsAsTransparentTexts = true;
// savingOptions.SaveTransparentTexts = true;

// Save the document
pdfSourceFile.save("pdfto.html", savingOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF to Images Conversion" %}}
Converting PDF pages into images including TIFF, JPEG, BMP, PNG, etc is easy within Java based applications using code snippets listed below. Developers can iterate through PDF pages and render Page by Page to required image format. Developers can set the horizental and vertical resolution of images using [Resolution class](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/Resolution). Create relevant image device object like [PngDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/PngDevice), [JpegDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice), [BmpDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/BmpDevice), [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) having the resolution as paratmer. Call the Process method to convert PDF page to Image and close the stream after conversion.
{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Converter Code" %}}
```cs
// Load the source File
Document pdftoImage = new Document("input.pdf");

// Loop through all the pages of PDF file
for (int pageNumber = 1; pageNumber <= pdftoImage.getPages().size(); pageNumber++) {

// Create stream object to save the output image using java.io OutputStream class
OutputStream imgStream = new FileOutputStream("pdf-to-image-" + pageNumber + ".png");

// Create Resolution object
Resolution rsl = new Resolution(300);

// Create relevant Image Device object with particular resolution
// It may be BmpDevice, JpegDevice, TiffDevice etc
PngDevice imgDevice = new PngDevice(rsl);

// Convert page by page and save the image to stream
imgDevice.process(pdfDocument.getPages().get_Item(pageNumber), imgStream);

// Close the stream
imgStream.close();
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-bmp pdf-to-tiff pdf-to-png pdf-to-gif pdf-to-jpeg" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF Parser API Other Supported Conversions" %}}
Java PDF Parsing API loads other multiple [formats](https://docs.aspose.com/pdf/java/supported-file-formats/) for parsing and conversion. API loads the relevant supported format and save into the required format.
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="epub-to-pdf html-to-pdf md-to-html md-to-pdf pcl-to-pdf tex-to-pdf" >}}