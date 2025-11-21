+++
title = "Schedule"
description = "Schedule"
+++
> All times are local. Parallel tracks run in separate rooms at Flinders University’s <a href="https://maps.app.goo.gl/rys2cTivJJn5aD4bA" target="_blank" rel="noopener noreferrer">Festival Plaza</a>.
> <h5> Room allocations and set-up information can be found here : <a href="https://blackochrelabs.au/abacbs2025_workshops/index.html">ABACBS/BiocAsia Workshop Schedule</a>.</h5>
<style>
  .schedule-grid{
    width:100%;
    border-collapse:collapse;
    table-layout: fixed;              /* ensure columns obey widths */
    font-size:1.6rem;
    line-height:1.45;
    text-align:center;
    --time-col: 14%;                  /* single source of truth */
  }
  .schedule-grid th, .schedule-grid td{
    border:1px solid #d1d5db;
    padding:14px 16px;
    vertical-align:middle;
  }
  .schedule-grid th{ background:#eef2f7; text-align:center; }
  .schedule-grid a{ text-decoration:none; }
  .schedule-grid a:hover{ text-decoration:underline; }

  /* Column widths (apply to BOTH tables) */
  .schedule-grid .col-time  { width: var(--time-col); white-space:nowrap; font-weight:700; }
  .schedule-grid .col-track { width: calc((100% - var(--time-col)) / 2); }

  /* Cell tints */
  .welcome{ background:#b7f7b3; font-weight:700; }
  .closing{ background:#b7f7b3; font-weight:700; }
</style>

### Thursday, 27 November

<table class="schedule-grid">
  <colgroup>
    <col class="col-time">
    <col class="col-track">
    <col class="col-track">
  </colgroup>
  <thead>
    <tr>
      <th>Time</th>
      <th>Microbiome/Metagenomics</th>
      <th>Single-Cell &amp; Spatial Omics</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>08:30–09:00</td>
      <td class="welcome" colspan="2">Welcome to the BioCAsia Workshops</td>
    </tr>
    <!-- Morning block -->
    <tr>
      <td>09:00–10:30</td>
      <!-- Microbiome spans to 12:30 -->
      <td class="long-session" rowspan="2">
        <a href="/abstracts/orchestrating-microbiome-bioconductor">
          Orchestrating Microbiome Analysis with Bioconductor
        </a>
      </td>
      <!-- Single-Cell spans to 12:30 -->
      <td class="long-session" rowspan="2">
        <a href="/abstracts/scdney-spatial-relationships">
          Unlocking single-cell spatial omics analyses with SCDNEY: Characterising spatial relationships between cells
        </a>
      </td>
    </tr>
    <tr>
      <td>11:00–12:30</td>
    </tr>
    <!-- Afternoon block -->
    <tr>
      <td>13:30–15:00</td>
      <!-- Microbiome spans to 17:00 -->
      <td class="long-session" rowspan="2">
        <a href="/abstracts/making-sense-of-metagenomes">
          Making Sense of Metagenomes: From Bugs to Biological Insight
        </a>
      </td>
      <td class="short-session">
        <a href="/abstracts/tidyomics-streamline">
          Streamline spatial and transcriptomic analysis with tidyomics
        </a>
      </td>
    </tr>
    <tr>
      <td>15:30–17:00</td>
      <td class="short-session">
        <a href="/abstracts/clustsignal-spatial-clustering">
          Spatial clustering with ClustSIGNAL – a spatial transcriptomics data analysis method
        </a>
      </td>
    </tr>
  </tbody>
</table>

### Friday, 28 November

<table class="schedule-grid">
  <colgroup>
    <col class="col-time">
    <col class="col-track">
    <col class="col-track">
  </colgroup>
  <thead>
    <tr>
      <th>Time</th>
      <th>Single-Cell Omics</th>
      <th>Spatial Omics</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>09:00–10:30</td>
      <td class="short-session">
        <a href="/abstracts/ataclone-scatac">
          ATAClone: cancer clone identification and copy number estimation from single-cell ATAC-seq
        </a>
      </td>
      <td class="long-session" rowspan="2">
        <a href="/abstracts/spanorm-phispace-jazzpanda">
          Spatial transcriptomics normalisation and phenotyping using SpaNorm, PhiSpace and jazzPanda
        </a>
      </td>
    </tr>
    <tr>
      <td>11:00–12:30</td>
      <td class="short-session">
        <a href="/abstracts/mastr-smartid">
          Advanced Marker Identification and Data Analysis with <em>mastR</em> and <em>smartid</em>
        </a>
      </td>
    </tr>
    <tr>
      <td>13:30–15:00</td>
      <td class="short-session">
        <a href="/abstracts/benchmarkinsights">
          Interpreting benchmarking results with BenchmarkInsights
        </a>
      </td>
      <td class="short-session">
        <a href="/abstracts/domino-hoodscanr-scider">
          Interrogating spatial transcriptomics: hands-on spatial domain, neighborhood &amp; density analysis with DOMINO, hoodscanR and scider
        </a>
      </td>
    </tr>
    <tr>
      <td>15:00–15:30</td>
      <td class="closing" colspan="2">Closing Comments</td>
    </tr>
  </tbody>
</table>
