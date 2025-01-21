<% tp.date.now("Do MMMM YYYY") %>
<% tp.date.yesterday("Do MMMM YYYY") %>
<% tp.date.tomorrow ("Do MMMM YYYY") %>

<% tp.date.now("YYYY-MM-DD", "p-1M") %>
date but one month ago

<% tp.date.now("Do MMMM YYYY", "P+1Y") %>
date but one year in the future

[[<% tp.date.now("Do MMMM YYYY", "P-1Y") %>]]
Last year's date but as a link