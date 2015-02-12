AUTHOR=Michael Cumming
PRESENTATION-VENUE=Telus_VisualAnalyticsLab
DATE-OF-PRESENTATION=2015-02-24
#-----------------------------------------------------------------------#
FILENAME="$(PRESENTATION-VENUE)_$(DATE-OF-PRESENTATION)"
# footer set in rst content instead
FOOTER="$(PRESENTATION-VENUE) | $(AUTHOR) | $(DATE-OF-PRESENTATION)"


#use: 'make slides' on the command line
#revise dates and venues above, as required
slides:
	rst2pdf slides.rst -b1 -s stylesheet.json -o $(FILENAME).pdf

slidesTest:
	rst2pdf slides.rst -b1 --footer=$(FOOTER) -s stylesheet.json -o $(FILENAME).pdf


