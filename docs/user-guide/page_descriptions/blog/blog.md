---

<!-- HTML format allows us to add a styled caption under the image-->
<p style="float:right; margin-left: 50px; margin-top: 5px; font-size: .8em">
  <img src="../../../../features/screenshots/blog.png"  width = "350px">
  <br><i>Example Blog Article</i>
</p>

The ***Blog Page*** is for adding your own family stories.  These stories can be for any reason and may include pictures as well.  As you develop your genealogy database and compile more interesting details about your family, you will want to add stories to give context to your family history.  Blogs can be a great way to capture interviews with older family members and pass down details of your family history.

---

##	A Blog is a ***Source***

!!!Note
	If you have not already read the section of this manual on [<u>Source Records</u>](../../../db_concepts/record_types/record_types/#source-records), then you should do so first.

Of all the Record Types available in Gramps, a ***Blog*** is not one of them.  "***Records***" are bland reading, whereas family stories can be much more engaging and enjoyable to read.  We felt Gramps Web needed the ability to display such engaging stories and so we "*borrow*"  the ***Source Record Type*** in order to create a Blog Article.

This means that all Blogs ***ARE*** sources and all blogs <u>will</u> show up in the Sources List; however, Source Records used as Blogs have a few special attributes that will allow Gramps Web to distinguish the Source Record as a Blog and subsequently display them collectively in the ***Blog*** section of Gramps Web. For a Source Record to be a Blog, the following bullet points apply:

*	The Source Record **MUST** have a tag attached named ***"Blog"***, (case-sensitive)

*	The Title of the Blog comes from the Title attribute of the Source Record

* 	The Author of the Blog comes from the Author attribute of the Source Record

*	The main text of the Blog comes from the Source Record's ***Notes*** attribute.

*	The first image (if any) in the Source Record's [<u>gallery</u>](../../../db_concepts/record_attributes/record_attributes/) will be the Blog's leading image.

*	Any additional media in the Source Record's gallery will be displayed under the main text of the Blog.


!!!Miscellaneous
	*	If using Gramps Desktop and synchronizing Records, the above bullet points still apply; therefore, you may create Blog Posts for Gramps Web via Gramps Desktop, though Gramps Desktop does NOT have Blogs.
	*	The URL of the blog post also contains the Gramps ID of the corresponding source, so an article at `yourdomain.com/blog/S0123` corresponds to the source at `yourdomain.com/source/S0123`.
	*	At the bottom of every blog post, there is a [DETAILS] button that will take you to the Source's ***Record View***

