<h2 id="publications">Publications</h2>

{% assign selected_papers = site.data.publications.main | where: "selected", true %}
<h3 class="pub-subhead" id="selected-publications">Selected publications</h3>
<p class="section-note">First-author and equal-contribution papers (<sup>*</sup> contributed equally; <sup>&dagger;</sup> co-corresponding author).</p>
{% include pub-list.html papers=selected_papers %}

<h3 class="pub-subhead" id="all-publications">All publications</h3>
<p class="section-note">See the complete list on <a href="https://www.ncbi.nlm.nih.gov/myncbi/yiyun.lin.4/bibliography/public/" target="_blank" rel="noopener">NCBI My Bibliography</a> or <a href="{{ site.google_scholar }}" target="_blank" rel="noopener">Google Scholar</a>.</p>
