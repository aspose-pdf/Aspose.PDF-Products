---
title: Convert PDF to Byte Array via C#
weight: 7690
url: /net/conversion/pdf-to-byte-array/
description: C# Sample code for PDF to Byte Array conversion. Use this code for PDF to Byte Array conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert PDF to byte array via C#" h2="Native and high performance Adobe Acrobat PDF to byte array conversion or vice versa for data processing using server side .NET APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/net" installationsDocsLink="https://docs.aspose.com/pdf/net" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/net" learnAsLink="https://docs.aspose.com/pdf/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array is helpful for data processing or storing. You can convert PDF file to Byte Array as well as a **Byte Array to PDF** using C#. In order to convert PDF to byte array, we’ll use
 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net)
 API that offers different features for PDF document manipulation and conversion using .NET platform.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to Byte Array via C#" %}}

{{% blocks/products/pf/agp/text %}}

 It is easy for the developers to load & convert PDF files to byte array for further manipulation tasks in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Include the namespace in your class file
1. Load input PDF File
1. Initialize a Byte Array
1. Initialize FileStream object
1. Load the contents into the byte array
1. Process byte array as of your requirement

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Just make sure that system have Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms as well as development environment like Microsoft Visual Studio.

{{% /blocks/products/pf/agp/text %}}

- Install from command line as <code>nuget install Aspose.PDF</code> or via Package Manager Console of Visual Studio with <code>Install-Package Aspose.PDF</code>.
- Alternatively, get the offline MSI installer or all DLLs in a ZIP file from <a href="https://downloads.aspose.com/pdf/net">downloads</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows PDF to byte array C# Conversion" offSpacer="" %}}

```cs
// load PDF with an instance of Document
var document = new Document("template.pdf");
// Add an additional page
document.Pages.Add();
// create Memory Stream
var memoryStream = new System.IO.MemoryStream();
document.Save(memoryStream);
// create Byte Array with PDF content
var byteArray = memoryStream.ToArray();
System.Console.WriteLine(byteArray.Length);
```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="" %}}

A Document Processing Library to perform a wide range of document management and manipulation tasks including PDF generation, editing, conversion, rendering and printing. .NET Word API supports all of word-processing formats as well as allows exporting or **converting PDF to Word**, HTML, fixed-layout and most commonly used image & multimedia formats.

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. PDF files can be opened in Adobe Acrobat Reader/Writer as well in most modern browsers like Chrome, Safari, Firefox via extensions/plug-ins. Most of the commercially available software suites also offer conversion of their documents to PDF file format without the requirement of any additional software component.

{{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert other file formats into byte array or vice versa including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-doc/" name="PDF To DOC" description="Microsoft Word Binary Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-html/" name="PDF To HTML" description="Hyper Text Markup Language" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-docx/" name="PDF To DOCX" description="Office 2007+ Words Document" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-word/" name="PDF To Word" description="Office Word Documents" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-xls/" name="PDF To XLS" description="Excel Binary Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-xlsx/" name="PDF To XLSX" description="OOXML Excel File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-xps/" name="PDF To XPS" description="XML Paper Specifications" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-excel/" name="PDF To Excel" description="Microsoft Excel Files" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-pptx/" name="PDF To PPTX" description="Open XML presentation Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/net/conversion/pdf-to-png/" name="PDF To PNG" description="Portable Network Graphics" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
