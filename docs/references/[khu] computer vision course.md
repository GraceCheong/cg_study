<h1>computer vision doc</h1>

<h2>what to follow?</h2>

<h4>previous class of seung kyu lee, all sources are from http://cvlab.khu.ac.kr/cv18.html</h4>

<br>
<table>
<tr>
<td>
Instructor
</td><td>&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td>
[E&amp;I Bldg. Room #310-2] <b>Seungkyu Lee</b>, Email: seungkyu(at)khu.ac.kr
</td>
</tr>
<tr>
<td>
Reference Books
</td><td>&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td>
<a href="http://szeliski.org/Book/">"Computer Vision: Algorithms and Applications" by Richard Szeliski</a><br>
<a href="http://www.google.co.kr/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=1&amp;sqi=2&amp;ved=0CCcQFjAA&amp;url=http%3A%2F%2Fwww.itu.dk%2Fcourses%2FSIGB%2FF2011%2Funtitled%2520folder%2FReading%2FIntroductory%2520Techniques%2520for%25203D%2520Computer%2520Vision.pdf&amp;ei=Snv9U7XgIYWF8gXEmYLgCA&amp;usg=AFQjCNFroT86l5dRYF2CmrbRbgD55vkbvg&amp;sig2=pEmvQ2R7dZYPlO8OyD2GIA&amp;bvm=bv.74035653,d.dGc&amp;cad=rjt">"Introductory Techniques for 3D Computer Vision"<br>
</a><a href="http://www.google.co.kr/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=2&amp;cad=rja&amp;uact=8&amp;sqi=2&amp;ved=0CC4QFjAB&amp;url=http%3A%2F%2Fwww.itu.dk%2Fcourses%2FSIGB%2FF2011%2Funtitled%2520folder%2FReading%2FRelatedBooks%2FIntroduction%2520to%25203D%2520CV%2520techniqes.pdf&amp;ei=rHr9U77IN8bq8AXI24DoCg&amp;usg=AFQjCNGLfSx9Nm_ULVXRhCNkLOLMjlnNKw&amp;sig2=h39u5LoxcFtI9RhvDwCn3A&amp;bvm=bv.74035653,d.dGc">"An Introduction to 3D Computer Vision Techniques and Algorithms" by Boguslaw Cyganek, J. Paul Siebert</a><br>
</td>
</tr>
<tr>
<td>
Additional Materials
</td><td>&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td>
<a href="http://cs.brown.edu/courses/cs143/docs/matlab-tutorial/index.html">Matlab Tutorial #1</a><br>
</td>
</tr>
<tr>
<td>
Evaluation
</td><td>&nbsp;&nbsp;&nbsp;&nbsp;</td>
<td>
Final project. 30%, Mid exam. 30%, Assignment 30%, Attendance 10%
</td>
</tr>
</tbody></table><font face="arial,sans-serif" size="4">
<br><br>
Assignment #1<br>
1. 2차원 LoG 필터를 Gaussian 필터와 Laplacian 필터를 이용하여 구현.<br>
* 커널 사이즈 및 std는 적절히 설정 <br>
2. 1번에서 구현한 LoG를 근사하는 Difference of Gaussian 구현.<br>
3. 1번,2번 필터를 각각 이용하여 필터링한 결과 영상 비교.<br>
Due 23:59 Oct.23 by email to sud0303(at)naver.com <br>
<br><br>
Assignment #2<br>
Homography 실습코드중에서,<br>
1. Homography matrix를 계산하는 함수를 자신의 코드로 대체하여 직접 구현 <br>
2. 얻어진 Homography matrix를 이용하여 warping을 수행하는 부분을 자신의 코드로 직접 구현 <br>
3. 1번,2번 을 이용하여 stitching 한 결과 영상을 실습 코드 결과와 비교.<br>
Due 23:59 Nov.15 by email to sud0303(at)naver.com <br>
<br><br>
<b>Course Schedule</b>

<br>

<table>
<tbody><tr><td>Week 1</td><td>&nbsp;&nbsp;</td>
<td>Sep. 4<br>Sep. 6</td><td>&nbsp;&nbsp;</td><td>
Class Introduction <a href="http://cvlab.khu.ac.kr/CVLecture1.pdf">Lecture Slide #1</a><br>
Introduction to modern computer vision <a href="http://cvlab.khu.ac.kr/CVLecture2.pdf">Lecture Slide #2</a><br>
</td></tr>
<tr><td>Week 2</td><td>&nbsp;&nbsp;</td>
<td>Sep. 11<br>Sep. 13</td><td>&nbsp;&nbsp;</td><td>
Intensity Surfaces, Gradients and Linear Operators <a href="http://cvlab.khu.ac.kr/CVLecture3.pdf">Lecture Slide #3</a><br>
Edge Detection <a href="http://cvlab.khu.ac.kr/CVLecture4.pdf">Lecture Slide #4</a>
</td></tr>
<tr><td>Week 3</td><td>&nbsp;&nbsp;</td>
<td>Sep. 18<br>Sep. 20</td><td>&nbsp;&nbsp;</td><td>
LoG, Template Matching and Corner <a href="http://cvlab.khu.ac.kr/CVLecture5.pdf">Lecture Slide #5</a><br>
Correspondence Matching <a href="http://cvlab.khu.ac.kr/CVLecture6.pdf">Lecture Slide #6</a>
</td></tr>
<tr><td>Week 4</td><td>&nbsp;&nbsp;</td>
<td>Sep. 25<br>Sep. 27</td><td>&nbsp;&nbsp;</td><td>
No Calss (Holiday) <br>
Camera Model &amp; Stereo <a href="http://cvlab.khu.ac.kr/CVLecture7.pdf">Lecture Slide #7</a>
</td></tr>
<tr><td>Week 5</td><td>&nbsp;&nbsp;</td>
<td>Oct. 2<br>Oct. 4</td><td>&nbsp;&nbsp;</td><td>
Stereo using Dynamic Programming <a href="http://cvlab.khu.ac.kr/CVLecture8.pdf">Lecture Slide #8</a><br>
Parameter estimation &amp; RANSAC &amp; Hough <a href="http://cvlab.khu.ac.kr/CVLecture9.pdf">Lecture Slide #9</a>
</td></tr>
<tr><td>Week 6</td><td>&nbsp;&nbsp;</td>
<td>Oct. 9<br>Oct. 11</td><td>&nbsp;&nbsp;</td><td>
No Calss (Holiday) <br>
Active Contours <a href="http://cvlab.khu.ac.kr/CVLecture10.pdf">Lecture Slide #10</a> <a href="http://cvlab.khu.ac.kr/cvcode1.zip"> 실습코드 #1</a>
</td></tr>
<tr><td>Week 7</td><td>&nbsp;&nbsp;</td>
<td>Oct. 16<br>Oct. 18</td><td>&nbsp;&nbsp;</td><td>
Machine learning in low-level vision <a href="http://cvlab.khu.ac.kr/CVLecture10_1.pdf">Lecture Slide #10-1</a><br>
Image Mappings <a href="http://cvlab.khu.ac.kr/CVLecture11.pdf">Lecture Slide #11</a>
</td></tr>
<tr><td>Week 8</td><td>&nbsp;&nbsp;</td>
<td>Oct. 23<br>Oct. 25</td><td>&nbsp;&nbsp;</td><td>
Homography, Mosaicing and Stabilization <a href="http://cvlab.khu.ac.kr/CVLecture12.pdf">Lecture Slide #12</a><br>
Video Change Detection <a href="http://cvlab.khu.ac.kr/CVLecture13.pdf">Lecture Slide #13</a>
</td></tr>
<tr><td>Week 9</td><td>&nbsp;&nbsp;</td>
<td>Oct. 30<br>Nov. 1</td><td>&nbsp;&nbsp;</td><td>
<b> Mid-Term Exam</b> <br>
Visual Tracking <a href="http://cvlab.khu.ac.kr/CVLecture14.pdf">Lecture Slide #14</a> 
</td></tr>
<tr><td>Week 10</td><td>&nbsp;&nbsp;</td>
<td>Nov. 6<br>Nov. 8</td><td>&nbsp;&nbsp;</td><td>
Visual Tracking (Cont.), Shape <a href="http://cvlab.khu.ac.kr/CVLecture15.pdf">Lecture Slide #15</a><br>
<a href="http://cvlab.khu.ac.kr/CV_practice_2.zip"> 실습코드 #2</a>
</td></tr>
<tr><td>Week 11</td><td>&nbsp;&nbsp;</td>
<td>Nov. 13<br>Nov. 15</td><td>&nbsp;&nbsp;</td><td>
Local Feature &amp; Structure From Motion <a href="http://cvlab.khu.ac.kr/CVLecture16.pdf">Lecture Slide #16</a><br>
<a href="http://cvlab.khu.ac.kr/CV_practice_3.zip">실습코드 #3</a>, Pattern Detection <a href="http://cvlab.khu.ac.kr/CVLecture17.pdf">Lecture Slide #17</a>
</td></tr>
<tr><td>Week 12</td><td>&nbsp;&nbsp;</td>
<td>Nov. 20<br>Nov. 22</td><td>&nbsp;&nbsp;</td><td>
Object Recognition 1 <a href="http://cvlab.khu.ac.kr/CVLecture18.pdf">Lecture Slide #18</a><br>
Pattern Recognition <a href="http://cvlab.khu.ac.kr/CVLecture19.pdf">Lecture Slide #19</a>
</td></tr>
<tr><td>Week 13</td><td>&nbsp;&nbsp;</td>
<td>Nov. 27<br>Nov. 29</td><td>&nbsp;&nbsp;</td><td>
Object Recognition 2 <a href="http://cvlab.khu.ac.kr/CVLecture20.pdf">Lecture Slide #20</a> <b>Final Project</b> <a href="http://cvlab.khu.ac.kr/collected.zip">matlab sample codes</a><br>
Action Recognition <a href="http://cvlab.khu.ac.kr/CVLecture21.pdf">Lecture Slide #21</a>
</td></tr>
<tr><td>Week 14</td><td>&nbsp;&nbsp;</td>
<td>Dec. 4<br>Dec. 6</td><td>&nbsp;&nbsp;</td><td>
Scene Understanding <a href="http://cvlab.khu.ac.kr/CVLecture22.pdf">Lecture Slide #22</a><br>
<a href="http://cvlab.khu.ac.kr/CV_practice_4.zip">실습코드 #4</a>
</td></tr>
<tr><td>Week 15</td><td>&nbsp;&nbsp;</td>
<td>Dec. 11<br>Dec. 13</td><td>&nbsp;&nbsp;</td><td>
3D Reconstruction using Color <a href="http://cvlab.khu.ac.kr/CVLecture23.pdf">Lecture Slide #23</a><br>
3D Reconstruction using RGBD <a href="http://cvlab.khu.ac.kr/CVLecture24.pdf">Lecture Slide #24</a>
</td></tr>
<tr><td>Week 16</td><td>&nbsp;&nbsp;</td>
<td>Dec. 18<br>Dec. 20</td><td>&nbsp;&nbsp;</td><td>
Light Field and Integral Imaging <a href="http://cvlab.khu.ac.kr/CVLecture25_1.pdf">Lecture Slide #25</a> <br> 
Vision for Graphics <a href="http://cvlab.khu.ac.kr/CVLecture26.pdf">Lecture Slide #26</a> 
</td></tr>
</table>


