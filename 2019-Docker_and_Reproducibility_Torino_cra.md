

#### PRACTICAL COURSE

# Docker and Reproducibility 
### Turin, Italy 13-24 June 2019

<table style="width:100%">
   <tr>
     <td><img src="./img/logoCorso.png" alt="Course Logo" height="200" width="700"></td>
     <tr/>
</table>


<table border="0">
<tr>
	<td><a href="https://elixir-iib-training.github.io/website/"><img src="./img/logo_iib.png" height="110" width="230"></a>	
	</td>
	<td>
	<td><a href="http://www.unito.it"><img src="./img/logo_unito.png" height="100" width="200"></a>
	</td>
	</td>
	</tr>
	<tr height="20"></tr>
	<tr>
	<td><a href=""><img src="./img/Logo_CNR_Italy.png" height="100" width="200"></a>
	</td>
	<td width="20"></td>
	<td><a href=""><img src="./img/Logo_INGM_web.jpeg" height="100" width="200"></a>
	</td>
</tr>
</table>
<br>

### Important Dates 
- Deadline for applications: **31-05-2019**
- Course date: **13-14 June 2019**
<br>
<br>

### Venue
University of Turin<br>
Molecular Biotechnology Center<br>
Via Nizza, 52<br> 
10126 Torino, Italy<br>
[https://www.mbc.unito.it/it](https://www.mbc.unito.it/it)
<br>


### Fee 
The course includes a fee of **60 Euros**, covering 4 coffee breaks and 2 lunches. Participants are expected to pay their own travel and hotel costs (if any).

A maximum of **15** candidates will be selected based on their need for the course and their prerequisites as emerging from the application form. Priority will be given to candidates from ELIXIR-IIB member institutions (see the list at the bottom) and ELIXIR nodes.
<br>

### Laptop
Participants will be requested to bring their own laptop; in case of need we can provide a computer to participants.
The mandatory requirements for the laptop are the presence of an ethernet plug/adapter and VNC client installation.


### Instructors
- [**Marco Beccuti**]() - Dep. of Molecular Biotechnology and Health Sciences, University of Torino, IT
- [**Raoul Bonnal**](https://elixir-iib-training.github.io/website/instructors/raoul_bonnal.html) -  Istituto Nazionale Genetica Molecolare "Romeo ed Enrica Invernizzi"​ (INGM), Milano, IT
<br>
<br>

### Helpers
- [**Raffaele A. Calogero**](https://elixir-iib-training.github.io/website/instructors/raffaele_calogero.html) - Dep. of Molecular Biotechnology and Health Sciences, University of Torino, IT
<br>
<br>

### Organisers
- [**Raffaele Calogero**](https://elixir-iib-training.github.io/website/instructors/raffaele_calogero.html) - Dep. of Molecular Biotechnology and Health Sciences, University of Torino, IT 
- [**Marco Chiapello**]() - Institute for Sustainable Plant Protection of the National Research Council of Italy (CNR)
- [**Marco Beccuti**]() - Dep. of Molecular Biotechnology and Health Sciences, University of Torino, IT
<br>
<br>

### Contact
For all kinds of queries, please contact the local organiser **Raffaele Calogero** at: <raffaele.calogero@unito.it>, tel: +39 0116706454, cel: +39 3333827080.<br>
<br>

### Course Description
Bioinformatics analysis typically integrate a large number of different tools, reference data to elaborate the input data and derive results. Reproducing the same analysis by other researchers is often a hard task as many pieces of the puzzle are missing from the used methodology. While the raw datasets are generally available; a clear workflow detailing the results reproducibility is often missing. Indeed, a simple list of tools used in the workflow could be not enough to guarantee the result reproducibility: different releases of the same tools or/and of the system libraries (exploited by such tools) might lead to sneaky reproducibility issues. The biggest obstacle in computational reproducibility is then to create a reliable, standalone, multiplatform and lightweight-working environment in which all the computational needs for a study are installed and frozen. Virtualization and containerization are the two approaches proposed to address this issue.

Virtual machines are very good at isolating system resources and entire working environments, while containers’ philosophy is to isolate only individual applications, not the entire system. Thus, containers are a lightweight fast and scalable alternative to Virtual machines when an completely isolated execution is not mandatory.

Docker is a container framework for Linux that allows a developer to make easier the creation, deployment, and execution of applications by using containers.
Recently it is becoming a promising approach to computational biology research reproducibility by:<br>
- Saving time and expenses on human and computational resources allocated to already performed analysis;
- Boosting communication between computational biologists working on similar topics;
- Enhancing transparency within the community;
- Granting open access computational knowledge to the community.
<br>
<br>


### Target audience
This course is aimed at providing to bioinformaticians and computer scientists the basic information to assemble docker images and use them.
<br>


### Course prerequisites
The participants will need to have basic shell scripting knowledge and basic experience in a scripting language, e.g. R,  Python, or others.
<br>

### Learning objectives
At the end of  this Docker Course the participant will be able to:
- Learn basics of Docker;
- Assess the advantages of a containerized software development & deployment;
- Use Docker engine features necessary for running containerized applications;
- Learn how to use  t Docker File and Docker Hub to create a Docker images;
- Learn the various networking mechanisms available in Docker.
<br>

### Learning outcomes
By the end of this course, the participant will be able:
- Embed  your own analysis pipelines in a Docker containers using docker file paradigm;
- Use Docker engine to execute containerized applications.
<br>
<br>



### [Application Form]()
<br>
<br>



### Preliminary programme

<table border="1">
<tr>
   <td colspan="4"><h3>Day 1 - </h3></td>
</tr>
<tr>
   <td height="50">09:00 - 09:30</td>
   <td colspan="3" height="50">Welcome, Intro & expectations</td>
</tr>
<tr>
   <td height="50">09:30 - 10:30</td>
   <td height="50">Lecture</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">General Information on Docker infrastructure</td>
</tr>
<tr>
   <td height="50">10:30 - 11:00</td>
   <td height="50" colspan="3">Coffee break</td>
</tr>
<tr>
   <td height="50">11:00 - 12:30</td>
   <td height="50">Lecture</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Introduction to docker survival commands</td>
</tr>
<tr>
   <td height="50">12:30 - 13:30</td>
   <td height="50" colspan="3">Lunch break </td>
</tr>
<tr>
  <td height="50">13:30 - 15:00</td>
  <td height="50">Practical</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Create a simple docker image</td>
</tr>
<tr>
   <td height="50">15:00 - 15:30</td>
   <td height="50" colspan="3">Coffee break</td>
</tr>
<tr>
  <td height="50">15:30 - 17:00</td>
  <td height="50">Practical</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Execute a simple docker image</td></tr>
<tr>
  <td height="50">17:00 - 18:00</td>
  <td height="50">Practical</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Build a docker image embedding R enviroment</td>
</tr>
<tr>
   <td colspan="3"><h3>Day 2 - </h3></td>
</tr>
<tr>
   <td height="50">09:00 - 09:30</td>
   <td colspan="3" height="50">Quick recapitulation of concepts from the previous day</td>
</tr>
<tr>
 <td height="50">09:00 - 10:30</td>
 <td height="50">Lecture </td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Introduction to docker file</td>
</tr>
<tr>
   <td height="50">10:30 - 11:00</td>
   <td height="50" colspan="3">Coffee break</td>
</tr>
<tr>
   <td height="50">11:00 - 12:30</td>
   <td height="50">Practical</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Create an image using docker file</td>
</tr>
<tr>
   <td height="50">12:30 - 13:30</td>
   <td height="50" colspan="2">Lunch break </td>
</tr>
<tr>
  <td height="50">13:30 - 15:00</td>
  <td height="50">Practical</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Embed a real applications in a docker container</td>
</tr>
<tr>
   <td height="50">15:00 - 15:30</td>
   <td height="50" colspan="3">Coffee break</td>
</tr>
<tr>
  <td height="50">15:30 - 17:00</td>
  <td height="50">Lecture</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Docker swarm in a nutshell</td>
</tr>
<tr>
  <td height="50">17:00 - 18:00</td>
  <td height="50">Practical</td>
   <td height="50">Beccuti/Bonnal/Calogero</td>
   <td height="50">Deploy services on a cluster using docker swarm.
</td>
</tr>
</table>


<br>
<br>

<h3>ELIXIR-IIB member institutions</h3>
<ul>
   <li> CNR (ELIXIR-IIB coordinator)</li>
   <li> CRS4</li>
   <li> CINECA</li>
   <li> INFN</li>
   <li> GARR</li>
   <li> Edmund Mach Foundation, Trento</li>
   <li> University of Roma "Sapienza"</li>
   <li> University of Bari</li>
   <li> University of Bologna</li>
   <li> University of Firenze</li>
   <li> University of Milano</li>
   <li> University of Milano Bicocca</li>
   <li> University of Padova</li>
   <li> University of Parma</li>
   <li> University of Roma "Tor Vergata"</li>
   <li> University of Salerno</li>
   <li> University of Tuscia </li>
</ul>

