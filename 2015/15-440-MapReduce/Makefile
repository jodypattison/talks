15-440-Averaging-with-MapReduce.html:
	ipython nbconvert --to html *.ipynb
	@sed -i \
		's/<title>\[\]<\/title>/<title>Simple Averaging: not so Simple with MapReduce<\/title>/g' \
		*.html
	@sed -i \
		's/body{background-color:white;position:absolute;left:0px;right:0px;top:0px;bottom:0px;overflow:visible;}/body{background-color:white;margin-left:auto;margin-right:auto;width:650px;zoom:1.25;overflow:visible;}/g' \
		*.html

clean:
	rm *.html
