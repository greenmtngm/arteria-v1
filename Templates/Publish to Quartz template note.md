<%*
let title = tp.file.title
if (title.startsWith("Untitled")){
	title = await tp.system.prompt("Title");
	await tp.file.rename(title);
}

 tR+="---"
 %>
 title:  <%* tR += title %>
 created: [[<% tp.date.now("Do MMMM YYYY HH:mm") %>]]
 last modified: <% tp.file.last_modified_date("Do MMMM YYYY HH:mm") %>
  <% draft: false %>
 Aliases:
 Tags:

-------

<%* tR+=title %>