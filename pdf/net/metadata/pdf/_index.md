---
title: View or Edit PDF Files Metadata via .NET 
weight: 2450
url: /net/metadata/pdf/ 
description: Try our On-Premise document metadata viewer or editing APIs to edit or view PDF format metadata on .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extract PDF Metadata via .NET" h2="Build your own .NET apps to add, edit, remove or extract metadata from PDF files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.PDF" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" apiHomeLink="https://products.aspose.app/pdf/family" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/net" installationsDocsLink="https://docs.aspose.com/pdf/net" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/net" learnAsLink="https://docs.aspose.com/pdf/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Extract PDF Metadata Using C#" %}}

 In order to extract PDF metadata, we’ll use
 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net) 
 API which is a feature-rich, powerful and easy to use document metadata API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.pdf) 
 package manager, search for
 **Aspose.PDF** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.PDF

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Extract Metadata of PDF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 First get the DocumentInfo object using the Info property of the Document object, then get the values of the individual properties.

{{% /blocks/products/pf/agp/text %}}

+  Load the PDF with an instance of Document
+  Get DocumentInfo using Document.Info property
+  Access & display different Document.Info properties

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.PDF for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
-  Development environment like Microsoft Visual Studio.
-  Aspose.PDF for .NET referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extract Metadata of PDF - C#" offSpacer="" %}}

```cs

// load PDF file with Document object
var document = new Aspose.Pdf.Document("template.pdf");
// get document information
var pdfInfo = document.Info;
// show document information
Console.WriteLine("Author: {0}", pdfInfo.Author);
Console.WriteLine("Creation Date: {0}", pdfInfo.CreationDate);
Console.WriteLine("Keywords: {0}", pdfInfo.Keywords);
Console.WriteLine("Modify Date: {0}", pdfInfo.ModDate);
Console.WriteLine("Subject: {0}", pdfInfo.Subject);
Console.WriteLine("Title: {0}", pdfInfo.Title);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.PDF for .NET API" %}}

 Aspose.PDF API can be used for PDF document manipulation and parsing within applications. One can create, modify, compress, secure, print or save PDF to TXT, HTML, PCL, XFA, XML, XPS, EPUB, TEX, Images and more formats. Aspose.PDF is a standalone API and it does not depend on any software including Adobe Acrobat. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of PDF via Online App" sectionDescription="View & edit Metadata to PDF documents by using our [Live Demos](https://products.aspose.app/pdf/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PDF file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. PDF files can be opened in Adobe Acrobat Reader/Writer as well in most modern browsers like Chrome, Safari, Firefox via extensions/plug-ins. Most of the commercially available software suites also offer conversion of their documents to PDF file format without the requirement of any additional software component. Thus, PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become as part of source document.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="Using C#, One can also manipulate metadata of many other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="" name="" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}