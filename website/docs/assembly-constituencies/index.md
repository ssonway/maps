<style>

#acmaps {
    width: 700px;
    height: 800px;
}
#acmaps .info {
    padding: 6px 8px;
    font: 0.7rem Arial, Helvetica, sans-serif;
    background: white;
    background: rgba(255,255,255,0.8);
    box-shadow: 0 0 15px rgba(0,0,0,0.2);
    border-radius: 5px;
}
#acmaps .info h6 {
    font-size: 1.2rem;
    margin: 0 0 5px;
    color: #777;
}

</style>

# India - Assembly Constituencies


The Assembly Constituencies of India, Scraped from ECI's [Poling Station Locations](http://psleci.nic.in/) Website.

           
Before using this data, please note the following:
 
 1. The Assembly Constituencies for the states of  Jammu And Kashmir, Jharkhand, Assam, Manipur, Nagaland & Arunachal Pradesh, appear to be pre-delimitation boundaries.
 2. There is some shift in the data.
 3. Some Assemblies Constituency Names seem to be incorrect or Missing.
 4. The Assembly Constituencies in the State of Telengana are still marked as belonging to Andhra Pradesh
 5. The Union Territories of Andaman and Nicobar Islands, Chandigarh,  Dadra and Nagar Haveli, Daman and Diu, 
 and Lakshadweep do not have a state assembly.

<img width="250px" style="float:left" src="http://projects.datameet.org/logo/datameet_logo_v.1.2.png" > :

This projects run by [Data{Meet}](http://datameet.org/) community. DataMeet is a community of Data Science and
Open Data enthusiasts. Data{Meet} community encompass many people, ideas, projects, solutions, and challenges 
that using data in India presents. Join the [Google Group](https://groups.google.com/group/datameet) to be part 
of this community.


## Shapefile Attributes.
Each Constituency will have the following attributes.

- ST_CODE: Code of the states as per the Assembly Constituencies.
- ST_NAME: Name of the states as per the Assembly Constituencies.
- DT_CODE: District code of each state as per the Assembly Constituencies.
- DIST_NAME: Name of Districts as per the Assembly Constituencies.
- AC_NO: Numbers of Assembly Constituencies.
- AC_NAME: Name of Assembly-Constituencies.
- PC_NO: Numbers of Parliamentary-Constituencies.
- PC_NAME:Name of Parliamentary-Constituencies.
- PC_ID: IDs of the parliamentary-constituencies.
- STATUS: Status of each id of the parliamentary-constituencies.

# Quick View

<div id="acmaps" ></div>


## Download
You can download the whole repository as a zip file to get everything you want. Using the button below.
<a class="btn btn-lg btn-success" href="https://github.com/datameet/maps.git"> <i class="fa fa-download fa-2x pull-left"></i> Download Everything</a>
If you are in exploring mode then to go to the specific state map page. In state page you can see a very rough version of the state village map and notes related to that state map. You can also download the full version state map from state page. If you just want to download the map. <code>Right click on download link -&gt; Save link as</code>.

<!-- | State            |      Status  |  Download |
|-------------------|:---------:|------:|
| [Bihar - BR](br/) |  Complete | [Download](https://github.com/datameet/indian_village_boundaries/raw/master/br/br.geojson) |
| [Karnataka - KA](ka/) |  Complete     |   [Download](https://github.com/datameet/indian_village_boundaries/raw/master/ka/ka.geojson) |
| [Kerala - KL](kl/) | Complete |    [Download](https://github.com/datameet/indian_village_boundaries/raw/master/kl/kl.geojson) |
| [Goa - GA](ga/) | Complete |    [Download](https://github.com/datameet/indian_village_boundaries/raw/master/ga/ga.geojson) |
| [Gujarat - GJ](gj/) | Complete |    [Download](https://github.com/datameet/indian_village_boundaries/raw/master/gj/gj.geojson) |
 -->
## License
The dataset is shared under [Creative Commons Attribution 2.5 India](http://creativecommons.org/licenses/by/2.5/in/) license.

## Attribute

Please use the following lines to attribute the maps if you use in your work. You could link instead of printing 
the URLs in case of web projects.

Villages Maps Provided by Indian Village Boundaries Project [http://projects.datameet.org/indian_village_
boundaries/] by Data{Meet}. Its made available under the Open Database License (ODbL)[http://opendatacommons.org/
licenses/odbl/].

## Issues
If you have any issues with the maps, please report them on the github repository:
<p><a href="https://github.com/datameet/maps/issues"><button class="btn btn-primary" type="submit">Report Issue</button></a>
<a href="https://github.com/datameet/maps/issues"><button class="btn btn-primary" type="submit">Active Issues</button></a></p>
## Repository
<p><a class="btn btn-lg btn-success" href="https://github.com/datameet/maps/issues">
  <i class="fa fa-github fa-2x pull-left"></i> GitHub</a>   <a class="btn btn-lg btn-success" href="https://github.com/datameet/maps/issues">
  <i class="fa fa-git fa-2x pull-left"></i> GitLab</a></p>
## Community </div>
