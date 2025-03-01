# Professor Haiwei Dong 
## Professor of Computer Science  

<div style="display: flex;">

<div style="flex: 70%;">

### Biography  
Haiwei Dong is currently a Principal Researcher and Director with <a href="https://www.huawei.com/ca/">Huawei Canada</a>, and an Adjunct Professor with the <a href="https://www.uottawa.ca/en">University of Ottawa</a>. He was a Principal Engineer with Artificial Intelligence Competency Center, Huawei Technologies Canada, Toronto, ON, Canada, a Research Scientist with the University of Ottawa, Ottawa, ON, Canada, a Postdoctoral Fellow with New York University, New York City, NY, USA, a Research Associate with the University of Toronto, Toronto, ON, Canada, and a Research Fellow (PD) with the Japan Society for the Promotion of Science, Tokyo, Japan. He received the Ph.D. degree from Kobe University, Kobe, Japan in 2010 and the M.Eng. degree from Shanghai Jiao Tong University, Shanghai, China, in 2008. He is a Senior Member of IEEE, a Senior Member of ACM, and a registered Professional Engineer in Ontario. His research interests include artificial intelligence, multimedia, metaverse, and robotics. He also serves as a Column Editor of IEEE Multimedia Magazine; an Associate Editor of ACM Transactions on Multimedia Computing, Communications, and Applications; and an Associate Editor of IEEE Consumer Electronics Magazine.

Jane Doe is a Professor of Computer Science at XYZ University. Her research interests include **artificial intelligence**, *machine learning*, and data science. She has published over 100 papers in top-tier conferences and journals, contributing significantly to advancements in AI technologies.  

She received her PhD from ABC University in 2005 and joined XYZ University in 2010, where she leads the AI Research Group.  

---

### Awards and Honors  
- **Distinguished Researcher Award**, 2020  
- **Best Paper Award**, International AI Conference, 2018  

---

### Selected Publications  
- **Jane Doe**, John Smith, "Title of Paper", *Journal of Computer Science*, 2020. [Link](http://example.com)  
- **Jane Doe**, Alice Johnson, "Another Paper", *Proceedings of the International Conference on AI*, 2019. [Link](http://example.com)  
- [Full list of publications](http://example.com/publications)  

---

### Teaching  
- **CS101: Introduction to Computer Science**  
  An introductory course covering the basics of programming and computer science principles.  
- **CS501: Advanced Machine Learning**  
  A graduate-level course exploring cutting-edge topics in machine learning.  

---

### Recent News  
<div id="news">
  <div class="news-item" data-date="2023-10-01">**October 2023**: Gave a keynote at the AI Conference. [Read more](http://example.com/news1)</div>
  <div class="news-item" data-date="2023-09-15">**September 2023**: Published a new paper in *Journal of CS*. [Link](http://example.com/paper)</div>
  <div class="news-item" data-date="2023-08-01">**August 2023**: Received a research grant. [Details](http://example.com/grant)</div>
  <div class="news-item" data-date="2023-07-01">**July 2023**: Hosted an AI ethics workshop. [Details](http://example.com/workshop)</div>
  <button id="show-more">Show more</button>
</div>

</div>

<div style="flex: 30%; text-align: center;">

<img src="haiwei_dong.jpg" alt="Professor Jane Doe" width="200">  

**Contact**  
Email: [jane.doe@example.com](mailto:jane.doe@example.com)  
Office: Building A, Room 101  
Phone: (123) 456-7890  

[LinkedIn](http://linkedin.com/in/janedoe)  
[Google Scholar](http://scholar.google.com/citations?user=abcdefg)  

</div>

</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const newsItems = document.querySelectorAll('.news-item');
  const thresholdDate = new Date();
  thresholdDate.setMonth(thresholdDate.getMonth() - 6); // Hides news older than 6 months

  newsItems.forEach(item => {
    const itemDate = new Date(item.dataset.date);
    if (itemDate < thresholdDate) {
      item.style.display = 'none';
    }
  });

  document.getElementById('show-more').addEventListener('click', function() {
    newsItems.forEach(item => {
      item.style.display = 'block';
    });
    this.style.display = 'none';
  });
});
</script>
