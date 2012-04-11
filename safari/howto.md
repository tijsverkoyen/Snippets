# Install

1. Copy the url below
2. Replace "<your id>" with your personal Argenta netbanking id
3. Add a new bookmark, and use the code as the url.
4. Done

    javascript:id='<your id>';url='https://internetbanking.argenta.be/Argenta2/authenticationUCRNL.jsp'; if(location!=url) { location = url; alert('Reopen your bookmark after the page is loaded'); } else { document.getElementsByName('id')[0].value=id; }
	
# Use

If you open the bookmark while you are browsing the internet banking website it will fill in your id, if you are not on the website it will navigate to the url and show a warning that reminds you to open up the bookmark again.