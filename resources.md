---
title: Resources
---
There are many resources available to help you learn Python. You may want to explore or build skills in Python without a specific project in mind. 

<ul id="libinfo"></ul>

**Google/ Web Search**

Google can be really useful if you're just perusing something really broad or finding something really specific. 

Tips: take some time to find the right search terms. Copying and pasting error messages into Google can help you with troubleshooting.

**One-on-One Help**

There are probably others out there who can help you with your project. Asking for help is a great way to connect with other Python people near you!

Tips: Be clear with your ask- what do you want from this person? Write down specific questions to discuss. Remember that they may not remember what it’s like to not know a core concept.

**Websites, Tech Blogs, and GitHub**

Other people out there may have done an analysis similar to yours. They may have written up a guide on how to do it, where they struggled, and they may post their code! You may find others with a similar background and struggles that you can learn from.

Tips: Find people you like, who have the same interests, or who are doing interesting things. Or make your own!

**Documentation**

The information that comes with libraries and programming tools can show you how to use them and give you details about how they work.

Tip: These documents assume you have a base knowledge of how Python works and can be hard to read, especially if you are a beginner. Look for examples to see how the code needs to be written.

**Books**

There are a lot of guides, how-to books, and reference books out there.

Tips: Identify what kind of book you are looking for, and evaluate it on content and readability. Is it what you want to learn? Is it way too easy or too hard? Does it walk you through exercises and does it come with code you can download?

**Event (Hackathon, Conference)**

Events are a great place to get ideas or work as part of a team on a project. They are also a great place to make connections with people who have similar interests. 

Tips: Once you know a skill, a hackathon can be a great place to try it out; however it may be difficult to start learning a skill as a team tries to do a project.

**Local Python User Group**

Your local user group is a great place to meet other Python users and to get feedback on a Python project you did.

Tips: Presenting a project to your local user group is a great way to get feedback on tools you used, hear about other ways to do it, and learn ways to refactor your code and make it readable, Pythonic, and efficient.

**Online Class**

There are lots of different places to take free online classes. This is a great way to build deeper knowledge and skills but may not be a great resource for the middle of a project you want to get done!

Tips: Look for reviews to find well-executed classes, there are some bad ones out there. Read the syllabus to make sure it’s the content you want to learn. Be intentional about your goal for the class. Find others to join you in a cohort and meet up!

**In-Person Class, Workshop**

Live classes and workshops can be a great way to learn with access to an instructor who is familiar with teaching learners and can answer questions.

Tips: Try to find a class that is the right skill level for you. Look at the class materials or read the syllabus if possible. You want something that is challenging but also manageable. You may want to try and build some basic skills before the workshop to prepare.

<script
			  src="https://code.jquery.com/jquery-3.1.1.min.js"
			  integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8="
			  crossorigin="anonymous"></script>
<script src="https://raw.githubusercontent.com/fcheslack/libZoteroJS/master/build/libzotero.js" type="text/javascript"></script>
<script type="text/javascript">
var library;
var $libinfo=$("#libinfo");
$(function() {
  library = new Zotero.Library("group", 910878, "how_to_python");
  library.loadItems().then((response)=>{
    response.loadedItems.forEach((it)=>{
      $libinfo.append("<li>" + it.get("title") + "</li>");
    }); 
  });
});
</script>

