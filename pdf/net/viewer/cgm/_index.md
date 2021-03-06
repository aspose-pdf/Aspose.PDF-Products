---
title: View CGM File Formats via .NET
url: /net/viewer/cgm/
description: C# source code to load, render and display CGM documents on .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="CGM File Viewer for .NET" h2="View CGM documents in a browser without needing Adobe Acrobat or Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.PDF" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/net" installationsDocsLink="https://docs.aspose.com/pdf/net" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/net" learnAsLink="https://docs.aspose.com/pdf/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to View CGM File Using C#" %}}

In order to view CGM file, we’ll use <a href="https://products.aspose.com/pdf/net">Aspose.PDF for .NET</a> API which is a feature-rich, powerful and easy to use API for C# platform to be used with any Viewer. Open <a href="https://www.nuget.org/packages/aspose.pdf">NuGet</a> package manager, search for <b>Aspose.PDF</b> and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```powershell

PM> Install-Package Aspose.PDF

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to View CGM via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.PDF makes it easy for the developers to view the CGM file with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load CGM file with an instance of Document
1. Call the Document.Save method while passing SaveFormat.Html as parameters
1. Load resultant HTML in default browser with Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.PDF for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
- Development environment like Microsoft Visual Studio
- Aspose.PDF for .NET referenced in your project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# example code to view CGM file" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";
// load CGM with an instance of Document
var document = new Aspose.Pdf.Document("template.cgm");
// save document in HTML format
document.Save("output.html", Aspose.Pdf.SaveFormat.Html);
// load resultant HTML in defualt browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.PDF API can be used for PDF document manipulation and parsing within applications. One can create, modify, compress, secure, print or save PDF to TXT, HTML, PCL, XFA, XML, XPS, EPUB, TEX, Images and more formats. Aspose.PDF is a standalone API and it does not depend on any software including Adobe Acrobat.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View CGM" sectionDescription="Check our live demos to [View CGM](https://products.aspose.app/pdf/viewer/cgm) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload CGM file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly View the CGM file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="CGM" readMoreLink="https://docs.fileformat.com/page-description-language/cgm/" >}}
Computer Graphics Metafile (CGM) is free, platform-independent, international standard metafile format for storing and exchanging of vector graphics (2D), raster graphics, and text. CGM uses object-oriented approach and many function provisions for image production. CGM uses these object-oriented characteristics for remolding graphical elements to render an image. A metafile contains necessary information that defines other files. In CGM, a text based source file contains all graphical elements that can be later compiled into a binary file. Basically CGM is a way to facilitate 2D graphical data interchange, independent from any particular platform, or device.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}