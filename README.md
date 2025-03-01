# Professor Jane Doe  
## Professor of Computer Science  

<div style="display: flex; gap: 20px;">

<div style="flex: 70%;">

### Biography  
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
  <button id="show-more" style="margin-top: 10px;">Show more</button>
</div>

</div>

<div style="flex: 30%; text-align: center;">

<img src="jane_doe.jpg" alt="Professor Jane Doe" width="200" style="border-radius: 10px;">  

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
    const itemDate = new Date(item.getAttribute('data-date'));
    if (itemDate < thresholdDate) {
      item.style.display = 'none';
    } else {
      item.style.display = 'block';
    }
  });

  const showMoreButton = document.getElementById('show-more');
  showMoreButton.addEventListener('click', function() {
    newsItems.forEach(item => {
      item.style.display = 'block';
    });
    showMoreButton.style.display = 'none';
  });
});
</script>
