# computer-graphics-lab-7-solved
**TO GET THIS SOLUTION VISIT:** [Computer-Graphics Lab 7 Solved](https://www.ankitcodinghub.com/product/computer-graphics-lab-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92340&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Computer-Graphics Lab 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Write a program that draws a color-changing cube.

<ol>
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Start from the code in 7-Lighting&amp;Shading slides. Draw a flat-shaded cube. Make sure camera manipulation shortcuts ‘1’, ‘3’, ‘2’, ‘w’ work.</li>
<li>Use the following light setting:</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
lightPos = (3.,4.,5.,1.)

</div>
</div>
<div class="layoutArea">
<div class="column">
glLightfv(GL_LIGHT0, GL_POSITION, lightPos)

</div>
</div>
<div class="layoutArea">
<div class="column">
ambientLightColor = (.1,.1,.1,1.)

</div>
</div>
<div class="layoutArea">
<div class="column">
glLightfv(GL_LIGHT0, GL_AMBIENT, ambientLightColor)

</div>
</div>
<div class="layoutArea">
<div class="column">
specularObjectColor = (1.,1.,1.,1.)

</div>
</div>
<div class="layoutArea">
<div class="column">
glMaterialfv(GL_FRONT, GL_SPECULAR, specularObjectColor)

</div>
</div>
<div class="layoutArea">
<div class="column">
glMaterialfv(GL_FRONT, GL_SHININESS, 10)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
D. If you press or repeat a key, the diffuse &amp; specular color of the light and the ambient &amp; diffuse color of the object should be changed as shown in the Table:

Key

A S

D F Z

X C V

E. Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)

2. Write a program that draws a smooth-shaded cube.

<ol>
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Start from the code in 7-Lighting&amp;Shading slides. Make sure camera manipulation shortcuts ‘1’, ‘3’, ‘2’, ‘w’ work.</li>
<li>Use glDrawElements(), not glDrawArray(). Refer the code in 6-Viewing&amp;projection2, Mesh slides.</li>
</ol>
i. Hint: In Gouraud shading, one vertex has only one normal. This makes using glDrawElements() easier.

D. Use the following normal vector data:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Action

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the light color to red

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the light color to green

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the light color to blue

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the light color to white

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the object color to red

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the object color to green

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the object color to blue

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change the object color to white

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>If you press or repeat a key, the ambient &amp; diffuse color of the object should be changed as shown in the Table:
Key

R G

B
</li>
<li>Expected result: Uploaded LabAssignment7-2.mp4</li>
<li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>
</ol>
</div>
</div>
</div>
