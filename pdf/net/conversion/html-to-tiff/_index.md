---
title: Convert HTML to TIFF via C#
url: /net/conversion/html-to-tiff/
description: Sample code for HTML to TIFF C# conversion. Use API example code for batch HTML files to TIFF conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert HTML to TIFF via C#" h2="Export HTML documents to multiple formats including TIFF on .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/net" installationsDocsLink="https://docs.aspose.com/pdf/net" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/net" learnAsLink="https://docs.aspose.com/pdf/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert HTML to TIFF Using C#" %}}

 In order to convert HTML to TIFF, we’ll use
 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net)
 API which is a feature-rich, powerful and easy to use document manipulation and conversion API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.pdf)
 package manager, search for
 Aspose.PDF
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```powershell

PM> Install-Package Aspose.PDF

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert HTML to TIFF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET developers can easily load & convert HTML files to TIFF in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load HTML file with an instance of Document class
1. Create & set the instance of TiffDevice class with Size & Resolution
1. Call TiffDevice.Process method with page index & output file path as parameters


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the .NET conversion sample code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
- Development environment like Microsoft Visual Studio.
- Aspose.PDF for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows HTML to TIFF C# Conversion" offSpacer="" %}}

```cs
// load HTML with an instance of Document
var document = new Document("template.html", new HtmlLoadOptions());

// create an object of tiffDevice
var renderer = new Aspose.Pdf.Devices.TiffDevice();

// convert a particular page and save the image in TIFF format
renderer.Process(document, "output.tiff");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert HTML to TIFF" sectionDescription="Check our live demos for [HTML to TIFF conversion](https://products.aspose.app/pdf/conversion/html-to-tiff) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your HTML file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant TIFF file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 A PDF Processing Library to create cross-platform applications with the ability to generate, modify, convert, render, secure and print documents without using Adobe Acrobat. .NET PDF API offers compression, table creation, graph & image functions, hyperlinks, stamp and watermarking tasks, extended security controls & custom font handling.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Known as language of the web, HTML has evolved with requirements of new information requirements to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from server, where these are hosted, or can be loaded from local system as well. Each HTML page is made up of HTML elements such as forms, text, images, animations, links, etc. These elements are represented by tags such as img, a, p and several others where each tag has start and end. It can also embed applications written in scripting languages such as JavaScript and Style Sheets (CSS) for overall layout representation.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="tiff" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}
TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}