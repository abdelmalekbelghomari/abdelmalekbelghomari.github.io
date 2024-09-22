---
layout: post
title: Japan Internship Feedback 
---

After spending 4 months in Tokyo, Japan with PhD. Ryosuke Hosaka, here my feedback on this incredible journey I experienced.<br>

<img src="{{site.baseurl}}/images/me_with_the_yakuza.jpg" width="70%" style="display: block; margin-left: auto; margin-right: auto;"/>

## My wish :

First of all, I wanted to work in the field of AI in a foreign country to fulfill my desire for an internship abroad. I instantly thought about Japan as I had already been to Tokyo and the Kansai region as a tourist. After this trip, which I thoroughly enjoyed, I wanted to come back as a professional and spend more time in this country.

## My research :

While seeking an internship in Japan, I initially targeted business companies to gain my first professional experience in Software Development and AI. However, the language barrier became an issue. Most companies were looking for Japanese-fluent candidates, and I had only been studying Japanese for two weeks at the time. <br>Additionally, I wanted to expand my knowledge and apply my skills to a field beyond Software Engineering. That’s when I thought about joining a research laboratory. I focused on research in fields like medicine, biology, physics, or chemistry, as I have a background in physics and chemistry from my bachelor's degree.

After sending multiple emails and having several interviews, I finally chose to work at the [Neural Information Systems](https://sites.google.com/shibaura-it.ac.jp/nis/home?authuser=0) at [Shibaura Instite of Technology](https://www.shibaura-it.ac.jp/en/index.html). 

## Purpose of the Laboratory : 

Neural Networks have been created through biomimicry, mimicking the brain's architecture. But what if we could understand the brain through these artificial neurons? That's what we do at Hosaka's Laboratory. Instead of using classical perceptrons, we use bio-inspired neurons, following the electrical connectivity laws within the brain.

Here is what is explained on the laboratory's website:

*The Neuroinformation Systems Laboratory crosses neuroscience and machine learning, to understand the brain and to realise machine learning of the same mechanisms as the brain. Therefore, the common areas of neuroscience and machine learning are the research targets. The following areas are currently the subject of research:*

> Reinforcement learning <br> Reservoir computing <br> Stochastic resonance <br> Excitatory-inhibitory balance <br> Data assimilation

## My Research :

During my 4-month internship, I worked on Reservoir Computing.

I conducted research on Reservoir Computing models, particularly on Liquid State Machines, which are a type of Reservoir Computer. My goal was to identify and explore the echo state property in these models. You can find more information about it in the reports I have written.

<div class="pdf-viewer" id="pdf-viewer-paper" style="overflow-y: scroll; height: 80vh;"></div>

<script>
  const url = '{{site.baseurl}}/assets/Report_LSM_Belghomari_Abdelmalek.pdf'; // Adjust the path to your PDF file

  // Load the PDF document
  pdfjsLib.getDocument(url).promise.then(function(pdf) {
    const totalPages = pdf.numPages;

    // Loop through all the pages
    for (let pageNum = 1; pageNum <= totalPages; pageNum++) {
      // Fetch each page
      pdf.getPage(pageNum).then(function(page) {
        const scale = 1;
        const viewport = page.getViewport({ scale: scale });

        // Prepare a canvas for each page
        const canvas = document.createElement('canvas');
        const context = canvas.getContext('2d');
        canvas.height = viewport.height;
        canvas.width = viewport.width;

        // Append the canvas to the PDF viewer container
        document.getElementById('pdf-viewer-paper').appendChild(canvas);

        // Render the page into the canvas context
        const renderContext = {
          canvasContext: context,
          viewport: viewport
        };
        page.render(renderContext);
      });
    }
  });
</script>

<p>Can't view the PDF? <a href="{{site.baseurl}}/assets/Report_LSM_Belghomari_Abdelmalek.pdf" download>Download it here.</a></p>
You can find this report I made for my University too : 

<div class="pdf-viewer" id="pdf-viewer-report" style="overflow-y: scroll; height: 80vh;"></div>

<script>
  const url_report = '{{site.baseurl}}/assets/Belghomari_Abdelmalek_report.pdf'; // Adjust the path to your PDF file

  // Load the PDF document
  pdfjsLib.getDocument(url_report).promise.then(function(pdf) {
    const totalPages_inReport = pdf.numPages;

    // Loop through all the pages
    for (let pageNum = 1; pageNum <= totalPages_inReport; pageNum++) {
      // Fetch each page
      pdf.getPage(pageNum).then(function(page) {
        const scale_report = 1;
        const viewport_report = page.getViewport({ scale: scale_report });

        // Prepare a canvas for each page
        const canvas_report = document.createElement('canvas');
        const context_report = canvas_report.getContext('2d');
        canvas_report.height = viewport_report.height;
        canvas_report.width = viewport_report.width;

        // Append the canvas to the PDF viewer container
        document.getElementById('pdf-viewer-report').appendChild(canvas_report);

        // Render the page into the canvas context
        const renderContext_report = {
          canvasContext: context_report,
          viewport: viewport_report
        };
        page.render(renderContext_report);
      });
    }
  });
</script>

<style>
  .pdf-viewer {
    width: 100%; /* Full width */
    max-width: 800px; /* Optional: max width of the PDF viewer */
    margin: 0 auto; /* Centering the viewer */
    border: 1px solid #ccc; /* Optional: add a border */
    padding: 10px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); /* Optional: add shadow */
  }
</style>

<p>Can't view the PDF? <a href="{{site.baseurl}}/assets/Belghomari_Abdelmalek_report.pdf" download>Download it here.</a></p>

## My Experience : 

What I keep from this experience is all the knowledge I acquired in only 4 months. I also made life-time friends and managed to to exchange and discuss with many researchers from around the world. My english communication just kept to get better and same for my japanese. I discovered so many cultures, met numerous people and have unforgettable memories. 

I sincerely thank all the laboratory for this fabulous journey. If you ever read this, I hope to see you again guys and share another 川飯 with you !