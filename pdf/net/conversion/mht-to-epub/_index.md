---
title: Convert MHT to EPUB via C#
url: /net/conversion/mht-to-epub/
description: Sample code for MHT to EPUB C# conversion. Use API example code for batch MHT files to EPUB conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert MHT to EPUB via C#" h2="Export MHT documents to multiple formats including EPUB on .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="EPUB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/net" installationsDocsLink="https://docs.aspose.com/pdf/net" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/net" learnAsLink="https://docs.aspose.com/pdf/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert MHT to EPUB Using C#" %}}

 In order to convert MHT to EPUB, we’ll use
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert MHT to EPUB via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET developers can easily load & convert MHT files to EPUB in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load MHT file with an instance of Document
1. Call the Document.Save method while passing the output file path & SaveFormat.Epub as parameters
1. EPUB file will be saved at the specified path


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the .NET conversion sample code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
- Development environment like Microsoft Visual Studio.
- Aspose.PDF for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows MHT to EPUB C# Conversion" offSpacer="" %}}

```cs
// load MHT with an instance of Document
var document = new Document("template.mht", new MhtLoadOptions());

// save document in EPUBformat
document.Save("output.epub", Aspose.Pdf.SaveFormat.Epub);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert MHT to EPUB" sectionDescription="Check our live demos for [MHT to EPUB conversion](https://products.aspose.app/pdf/conversion/mht-to-epub) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your MHT file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant EPUB file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 A PDF Processing Library to create cross-platform applications with the ability to generate, modify, convert, render, secure and print documents without using Adobe Acrobat. .NET PDF API offers compression, table creation, graph & image functions, hyperlinks, stamp and watermarking tasks, extended security controls & custom font handling.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MHT" readMoreLink="https://docs.fileformat.com/web/mht/" >}}
A file with .mht extension is a MIME enabled archiving file format that contains different types of data into a single file. It can store data such as text, images, page styling in the form of CSS files, JavaScript, and other resources as embedded resources in it. MHT files, having MIME type message/rfc822, encapsulate all the contents of an HTML file as a single archive file for storing on archiving on storage devices. Software applications such as Microsoft Word lets you convert your WORD documents to MHT by exporting as MHT file. MHT files can be opened using popular browsers such as Microsoft Internet Explore and Google Chrome.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="epub" readMoreLink="https://docs.fileformat.com/ebook/epub/" >}}
Files with .EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. For example, on Mac OS, the pre-installed Books software provides the support for opening such files. In addition, there are a lot of compatible software available for smartphones, tablets and computers. EPUB file standards are maintained by the International Digital Publishing Forum (IDPF). The version EPUB 3 is also endorsed by the Book Industry Study Group (BISG), a leading book trade association for standardized best practices, research, information and events, for packaging of content.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}