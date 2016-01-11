##
## Makefile
## Login : <pepe@Marius.laforeuse.com>
## Started on  Wed Sep  3 16:27:46 2003 Pepe
## $Id: Makefile,v 1.1 2003-09-03 21:42:12 pepe Exp $
## 
## Copyright (C) 2003 Pepe
## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 2 of the License, or
## (at your option) any later version.
## 
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
## 
## You should have received a copy of the GNU General Public License
## along with this program; if not, write to the Free Software
## Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 USA
##

all:
	pdflatex cv.tex
	pdflatex cv.tex
	mv cv.pdf cv_Alexandre_Thibault_en.pdf
#	tex2pdf.sh cv.tex && mv cv.pdf cv_Alexandre_Thibault_en.pdf

clean:
	rm -f cv.aux cv.log *~

fclean: clean
	rm -f cv_Alexandre_Thibault_en.pdf