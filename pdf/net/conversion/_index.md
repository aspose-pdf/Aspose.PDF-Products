---
title: PDF File Conversion via C#
url: /net/conversion/
description: Convert PDF to Microsoft Word, Excel, PowerPoint Slides, HTML, Images and many other popular formats with just few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PDF Document Conversion via .NET" h2="Export PDF to Microsoft Office® Word, Excel, PowerPoint Presentations, Images, HTML and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
There are few cases when there is need to manipulate documents other then PDF while having the parsing data available in PDF formats. So for such applications there will be two scenarios either they add functionality of PDF parsing within their own solution or add the PDF conversion functionality to manipulate data as of supported formats. For the second scenario to **convert PDF to Word**, Excel, HTML, Images or any required format, implementing **C# PDF reader and converter** code within .NET based is simple. We are discussing here few cases so that programmers can modify these conversion code snippets as of their requirements.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to Word DOC DOCX and More Formats" %}}
C# PDF library supports all PDF to Word conversions. In case we are just converting Microsoft<sup>&reg;</sup> Word documents without any special settings, Then after loading the PDF file using [Document class](https://apireference.aspose.com/pdf/net/aspose.pdf/document), library's [Save method](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/4) will used with output Word document path and SaveFormat as parameters.  For the special cases where there is need to enhance the lines distance, image resolution and more settings, API has [DocSaveOptions](https://apireference.aspose.com/net/pdf/aspose.pdf/docsaveoptions) class that exposes all such settings.
{{% blocks/products/pf/feature-page-code h3="C# Code for PDF to Word Conversion" %}}

```cs
// Load the source PDF File
Document pdfFile = new Document("Source-PDF-File.pdf");

// For just simple PDF to Word Conversion

// pdfFile.Save("PDF-To-Word.doc", SaveFormat.Doc);

// Save using save options
// Create DocSaveOptions object
DocSaveOptions saveOpts = new DocSaveOptions();

// Set the recognition mode as Flow means Full recognition mode
saveOpts.Mode = DocSaveOptions.RecognitionMode.Flow;

// Other two modes are RecognitionMode.Textbox and RecognitionMode.EnhancedFlow

// Set the Horizontal proximity as 2.5
saveOpts.RelativeHorizontalProximity = 2.5f;

// Enable the value to recognize bullets during conversion process
saveOpts.RecognizeBullets = true;

// Save the resultant DOC file
pdfFile.Save("PDF-To-Word.doc", saveOpts);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-word pdf-to-doc pdf-to-docx" >}}

{{% blocks/products/pf/feature-page-section  h2="Save PDF as Excel Files" %}}
Specialized [SaveFormat.Excel](https://apireference.aspose.com/pdf/net/aspose.pdf/saveformat) Enumeration available for saving PDF to specific Microsoft Excel XLS XLSX output formats. Moreover, **.NET PDF Library** also have a speicific [ExcelSaveOptions class](https://apireference.aspose.com/pdf/net/aspose.pdf/excelsaveoptions) that not only deals saving to Excel formats but also provides different functions and properties for setting different attributes like exact output format, minimize number of worksheets and more.

{{% blocks/products/pf/feature-page-code h3="PDF to Excel C# Code" %}}

```cs
// Load PDF document
Document pdfDoc = new Document("sample-file.pdf");
// Initialize ExcelSaveOptions
ExcelSaveOptions opts = new ExcelSaveOptions();
// Set output Excel XLSX format
opts.Format = ExcelSaveOptions.ExcelFormat.XLSX;
// Minimize number of Worksheets
opts.MinimizeTheNumberOfWorksheets = true;
// Convert PDF to Excel output file
pdfDoc.Save("pdf-to-excel-output.xlsx", opts);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-excel pdf-to-xls pdf-to-xlsx" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to PowerPoint Presentations" %}}
.NET PDF API supports converting PDF pages to PowerPoint Presentation Slides with selectable text or images by rendering slides as images. Pattern of saving Portable Document Format to PowerPoint is almost same, Loading the file using Document class and then calling the Save method with output file path and SaveFormat as parameters. In case of rendering with special presentation options, Programmers can use [PptxSaveOptions class](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxsaveoptions) with any relevant specific rendering options. Calling the save method and passing the options as parameter.
{{% blocks/products/pf/feature-page-code h3="PDF to PowerPoint Conversion C# Code" %}}

```cs
// Load PDF document
Document pdfDocument = new Document("document.pdf");
PptxSaveOptions pptxOptions = new PptxSaveOptions();
pptxOptions.SlidesAsImages = true;
// Save output file
pdfDocument.Save("PDF to PPT.ppt", pptxOptions);
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Portable Document Format PDF to HTML Conversion" %}}
PDF Parsing Library supports saving PDF to HTML as whole as well as with embedded resources including images. Procedure of conversion is same as PDF to other formats for generic cases, like loading the source document and calling the Save method with output HTML file path and SaveFormat.Html as parameters. In case of saving with embedded resources, there is a [HtmlSaveOptions class](https://apireference.aspose.com/pdf/net/aspose.pdf/htmlsaveoptions) having multiple options like saving images to a specific folder during the conversion, splitting the resultant HTML into multiple pages and more.
{{% blocks/products/pf/feature-page-code h3="C# Code for PDF to HTML Conversion" %}}

```cs
// Load source PDF document
Document doc = new Document("source-input-file.pdf");

// Instantiate HTML Save options object
HtmlSaveOptions conversionOptions = new HtmlSaveOptions();

// Enabling option to embed all resources inside the HTML
conversionOptions.PartsEmbeddingMode = HtmlSaveOptions.PartsEmbeddingModes.EmbedAllIntoHtml;

// Specifying the separate folder for PDF to HTML with Images
conversionOptions.SpecialFolderForAllImages = "ImagesFolder";

// Specifying the splitting option for the resultant HTML into multiple pages
conversionOptions.SplitIntoPages = true;

doc.Save("converted-pdf-to.html", conversionOptions);
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to Images" %}}
Converting PDF pages into images including PNG, JPEG, TIFF, BMP etc is easy within .NET based applications using code snippets listed below. Developers can  loop through PDF pages after loading the file and convert Page by Page to required image format. Developers can set the horizental and vertical resolution of images using [Resolution class](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/resolution)
{{% blocks/products/pf/feature-page-code h3="Convert PDF Pages to Images C# Code" %}}

```cs
// Load document
Document srcFile = new Document("pdf-pages-to-image.pdf");

using (FileStream streamObj = new FileStream("pdf-to-image.jpeg", FileMode.Create)){

// Create Resolution object
Resolution resolution = new Resolution(300);

// Create Image device with specified attributes
// Width, Height, Resolution
JpegDevice renderToImages = new JpegDevice(500, 700, resolution);
// For BMP, PNG, TIFF it will be BmpDevice, PngDevice, TiffDevice respectively

// Convert a particular page and save the image to stream
renderToImages.Process(srcFile.Pages[1], streamObj);

// Close stream
streamObj.Close();

```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-bmp pdf-to-tiff pdf-to-png pdf-to-gif pdf-to-bmp" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF API Other Supported Conversions" %}}
C# PDF API loads other multiple [formats](https://docs.aspose.com/pdf/net/supported-file-formats/) for manipulation and conversion. API loads the relevant supported format and save into the required format.
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="cgm-to-pdf epub-to-pdf html-to-pdf md-to-html md-to-pdf pcl-to-pdf svg-to-png tex-to-pdf xps-to-html" >}}
