# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.

########################################################################
# Install public header files
########################################################################
install(FILES
    gr_bluetooth_multi_block.h
    gr_bluetooth_multi_LAP.h
    gr_bluetooth_multi_UAP.h
    gr_bluetooth_piconet.h
    gr_bluetooth_multi_hopper.h
    gr_bluetooth_multi_sniffer.h
    gr_bluetooth_packet.h
    tun.h
    DESTINATION include/gr-bluetooth
)
