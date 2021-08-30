---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
channels:
    - guru: swami vishvatmananda
      org: sadhana sadan ashram
      lang: hindi
      link: https://www.youtube.com/channel/UCVBRpMGGXxAKgm3UxzCcpHQ
    - guru: swami brahmananda
      org: kaivalya sopana
      lang: hindi
      link: https://www.youtube.com/channel/UC7ahgOP9X8riUl39nxgixFA
    - guru: swami vijayananda
      org: kailash ashram
      lang: hindi
      link: https://www.youtube.com/channel/UCPqECyffnKOhuYV-1GwAdkg
    - guru: br. pragyan chaitanya
      org: sadhana sadan ashram
      lang: hindi
      link: https://www.youtube.com/channel/UC_abXPZodhG0Oy_XepwiaCA
    - guru: srinivas jammalamadaka
      org:  --
      lang: sanskrit
      link: https://www.youtube.com/c/JammalamadakaSrinivas
    - guru: dravidacharya
      org: shastralayalam
      lang: english, tamil, hindi
      link: https://www.youtube.com/user/Shastralayam/playlists    
books:
    - name: laghu siddhanta kaumudi
      tika: pragya toshini (hindi)
      link: https://archive.org/details/lVSS_laghu-siddhant-kaumudi-mlbd-dharanand-shastri
    - name: tarka sangraha
      tika: --
      link: https://archive.org/details/tarkasangrahalaksanatippanirajanarayanashuklachowkambha_202003_601_s
    - name: tarka sangraha
      tika: nyaya bodhini, padakritya, balamanorama
      link: https://archive.org/details/tarkasangrahanyayabodhinipadakrutyachandrajasimhabalamanoramaguruprasadshastripa_202003_136_J
    - name: tarka sangraha
      tika: dipika and hindi vivarana
      link: https://archive.org/details/wg062/
    - name: artha sangraha
      tika: hindi dipika
      link: https://archive.org/details/ArthaSangrahaPanditSriShobhitMishra
    - name: tattvabodha
      tika: hindi by sw. vidyanand
      link: https://archive.org/details/TattvabodhaHindiKailash
    - name: tattvabodha
      tika: hindi by sw. divyanand
      link: https://archive.org/details/TattvabodhaAtmabodha
    - name: vedantasara
      tika: subodhini, vidvan manoranjani
      link: https://archive.org/details/VedantaSara1916WithTwoCOmmentariesNirnaySagarPress
---


<div class="vedanta-header p-3 pb-md-4 mx-auto text-center">
    <h1 class="display-4 fw-normal">Links</h1>
</div>

<h2 class="pb-2 border-bottom bg-light links-table-header">youtube channels</h2>

<div class="table-responsive">
    <table class="table table-striped table-sm">
        <thead>
            <tr>
                <th scope="col">acharya</th>
                <th scope="col">organization</th>
                <th scope="col">language</th>
                <th scope="col">link</th>
            </tr>
        </thead>
        <tbody>
        {% for c in page.channels %}
            <tr>
                <td>{{c.guru}}</td>
                <td>{{c.org}}</td>
                <td>{{c.lang}}</td>
                <td><a href="{{c.link}}">youtube channel</a></td>
            </tr>
        {% endfor %}
        </tbody>
    </table>
</div>

<h2 class="pb-2 border-bottom bg-light links-table-header">books (archive.org)</h2>

<div class="table-responsive">
    <table class="table table-striped table-sm">
        <thead>
            <tr>
                <th scope="col">book</th>
                <th scope="col">tika</th>
                <th scope="col">link</th>
            </tr>
        </thead>
        <tbody>
        {% for b in page.books %}
            <tr>
                <td>{{b.name}}</td>
                <td>{{b.tika}}</td>
                <td><a href="{{c.link}}">archive.org link</a></td>
            </tr>
        {% endfor %}
        </tbody>
    </table>
</div>
