###
###    Copyright (C) 2011 Huseyin Kerem Cevahir <kerem@mydlp.com>
###
###--------------------------------------------------------------------------
###    This file is part of MyDLP.
###
###    MyDLP is free software: you can redistribute it and/or modify
###    it under the terms of the GNU General Public License as published by
###    the Free Software Foundation, either version 3 of the License, or
###    (at your option) any later version.
###
###    MyDLP is distributed in the hope that it will be useful,
###    but WITHOUT ANY WARRANTY; without even the implied warranty of
###    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
###    GNU General Public License for more details.
###
###    You should have received a copy of the GNU General Public License
###    along with MyDLP.  If not, see <http://www.gnu.org/licenses/>.
###--------------------------------------------------------------------------

mavendir = $(datadir)/maven3/

install-data-hook:
	mkdir -p $(DESTDIR)$(mavendir) && \
		cp -af  bin \
			boot \
			conf \
			lib \
			LICENSE.txt \
			NOTICE.txt \
			README.txt \
			$(DESTDIR)$(mavendir)

