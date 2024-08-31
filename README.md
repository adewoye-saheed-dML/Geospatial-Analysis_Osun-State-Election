<h1>Osun State 2023 Presidential Election Geospatial Analysis</h1>
<p>This repository contains my geospatial analysis of the 2023 Presidential Election results for Osun State, Nigeria. The <a href="https://drive.google.com/file/d/1TNB1ltBPJONemPVyqPQMRPoGjqGAz0tM/view?usp=drive_link">data</a> was collected from INEC (Independent National Electoral Commission) and focuses on the polling units for the four major political parties: APC, PDP, LP, and NNPC. I used geospatial techniques to spot any unusual patterns or outliers in the data.</p>
<h2>What This Is About</h2>
<p>Elections can sometimes have results that stand out, so I decided to take a closer look at the 2023 Presidential Election in Osun State. By analyzing the distances between the polling units, I was able to identify some polling units that seemed a bit off compared to the others.</p>
<h2>How I Did It</h2>
<ol>
<li><strong>Data Collection:</strong> I got the data from INEC, which included the locations (latitude and longitude) of all the polling units in Osun State.</li>
<li><strong>Crunching the Numbers:</strong> I used a Python function called <code>distance_matrix</code> from the <code>scipy.spatial</code> library to calculate the distances between every pair of polling units.</li>
<li><strong>Spotting the Outliers:</strong> After running the numbers, I looked for polling units that were significantly different from the rest. These are the outliers I found.</li>
</ol>
<h2>What I Found</h2>
<p>Here are the top 3 outliers for each of the major parties:</p>
<h3>APC Outliers</h3>
<ol>
<li><strong>L.A. School, Eesadee</strong></li>
<li><strong>Ogunsua Gram. School, Esuyare</strong></li>
<li><strong>Open Space in Front of Baale Ile Aranyin (Aranyin Square)</strong></li>
</ol>
<h3>PDP Outliers</h3>
<ol>
<li><strong>Owode Comm. Pry School</strong></li>
<li><strong>Anuolu Junction</strong></li>
<li><strong>Secretariat</strong></li>
</ol>
<h3>LP Outliers</h3>
<ol>
<li><strong>Beulah Bapt. School, Ejigbo</strong></li>
<li><strong>Town Hall Iwara</strong></li>
<li><strong>Apostolic Pry. School, Oko-Ago</strong></li>
</ol>
<h3>NNPC Outliers</h3>
<ol>
<li><strong>Owode Comm. Pry School</strong></li>
<li><strong>Anuolu Junction</strong></li>
<li><strong>Secretariat</strong></li>
</ol>
<h2>Why It Matters</h2>
<p>These outliers might indicate something unusual happening in those areas. It&rsquo;s important to investigate further to ensure that everything was on the up-and-up during the election.</p>
<h2>How to Use This</h2>
<p>If you want to dig into this analysis yourself:</p>
<ol>
<li>Clone this repo.</li>
<li>Make sure you have Python installed, along with the <code>scipy</code> library (<code>pip install scipy</code> if you don&rsquo;t have it).</li>
<li>Run the analysis with the script provided.</li>
</ol>
<h2>Contributing</h2>
<p>Got ideas? Found something I missed? Feel free to open an issue or submit a pull request!</p>
