# Copyright (C) 2005-2010 MaNGOS <http://getmangos.com/>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

## Process this file with automake to produce Makefile.in

## Sub-directories to parse
SUBDIRS = dep doc sql src

## Additional files to include when running 'make dist'
# Win32 project workspace for Visual Studio .NET 2005
EXTRA_DIST = \
	win/mangosdVC80.sln \
	win/VC80/framework.vcproj \
	win/VC80/game.vcproj \
	win/VC80/mangosd.vcproj \
	win/VC80/realmd.vcproj \
	win/VC80/shared.vcproj \
	win/VC80/zlib.vcproj \
	win/VC80/g3dlite.vcproj

# Win32 project workspace for Visual Studio .NET 2008
EXTRA_DIST += \
	win/mangosdVC90.sln \
	win/VC90/framework.vcproj \
	win/VC90/game.vcproj \
	win/VC90/mangosd.vcproj \
	win/VC90/realmd.vcproj \
	win/VC90/shared.vcproj \
	win/VC90/zlib.vcproj \
	win/VC90/g3dlite.vcproj

# Win32 project workspace for Visual Studio .NET 2010
EXTRA_DIST += \
	win/mangosdVC100.sln \
	win/VC100/framework.vcxproj \
	win/VC100/game.vcxproj \
	win/VC100/mangosd.vcxproj \
	win/VC100/realmd.vcxproj \
	win/VC100/shared.vcxproj \
	win/VC100/zlib.vcxproj \
	win/VC100/g3dlite.vcxproj

ACLOCAL_AMFLAGS = -I m4

