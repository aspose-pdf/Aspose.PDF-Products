---
title: Convert XSLFO to XPS via C#
url: /net/conversion/xslfo-to-xps/
description: Sample code for XSLFO to XPS C# conversion. Use API example code for batch XSLFO files to XPS conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert XSLFO to XPS via C#" h2="Export XSLFO documents to multiple formats including XPS on .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XSLFO" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/net" installationsDocsLink="https://docs.aspose.com/pdf/net" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/net" learnAsLink="https://docs.aspose.com/pdf/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert XSLFO to XPS Using C#" %}}

 In order to convert XSLFO to XPS, we’ll use
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert XSLFO to XPS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET developers can easily load & convert XSLFO files to XPS in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load XSLFO file with an instance of Document
1. Call the Document.Save method while passing the output file path & SaveFormat.Xps as parameters
1. XPS file will be saved at the specified path


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the .NET conversion sample code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
- Development environment like Microsoft Visual Studio.
- Aspose.PDF for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows XSLFO to XPS C# Conversion" offSpacer="" %}}

```cs
// Instantiate XslFoLoadOption object
var options = new XslFoLoadOptions("template.xslt")
{
    // Set error handling strategy
    ParsingErrorsHandlingType = XslFoLoadOptions.ParsingErrorsHandlingTypes.ThrowExceptionImmediately
};
// Create Document object
var document = new Aspose.Pdf.Document("template.xml", options);

// save document in XPS format
document.Save("output.xps", Aspose.Pdf.SaveFormat.Xps);
```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert XSLFO to XPS" sectionDescription="Check our live demos for [XSLFO to XPS conversion](https://products.aspose.app/pdf/conversion/xslfo-to-xps) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your XSLFO file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant XPS file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 A PDF Processing Library to create cross-platform applications with the ability to generate, modify, convert, render, secure and print documents without using Adobe Acrobat. .NET PDF API offers compression, table creation, graph & image functions, hyperlinks, stamp and watermarking tasks, extended security controls & custom font handling.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XSLFO" readMoreLink="https://docs.fileformat.com/page-description-language/xslfo/" >}}
XSL-FO (XSL Formatting Objects) is a powerful stylesheet language for formatting XML documents. The semantics of the bounded form of paper and print are expressed by XSL-FO when the dimensions are fixed. In contrast to HTML, which represents the semantics of the unbounded form of a browser window with variable dimensions. The XML documents formatted by XSL-FO are mostly used to generate PDF files. XSL (Extensible Stylesheet Language) is a set of feature complete W3C technologies intended to design for the formatting and exchange of XML documents and XSL-FO is a part of this language. XSLT and XPath are also other parts of XSL.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="xps" readMoreLink="https://docs.fileformat.com/page-description-language/xps/" >}}
An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. This format was developed by Microsoft as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document. It is, in fact, more justified to say that XPS is an attempt on PDF, but couldn't get enough popularity as owned by PDF for a number of reasons. Microsoft provides XPS Document Writer by default from Windows 7 onwards for the creation of XPS files. XPS files can be generated by selecting the "Microsoft XPS Document Writer" as printer while printing the document.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}