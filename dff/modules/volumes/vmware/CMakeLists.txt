# DFF -- An Open Source Digital Forensics Framework
# Copyright (C) 2009-2013 ArxSys
# This program is free software, distributed under the terms of
# the GNU General Public License Version 2. See the LICENSE file
# at the top of the source tree.
#  
# See http://www.digital-forensic.org for more information about this
# project. Please do not directly contact any of the maintainers of
# DFF for assistance; the project provides a web site, mailing lists
# and IRC channels for your use.
# 
# Author(s):
#  Jeremy MOUNIER <jmo@digital-forensic.org>

dff_cpp_module(VMWARE
  CPP_FILES vmware.cpp diskDescriptor.cpp extent.cpp link.cpp vmnode.cpp
  SWIG_FILE vmware.i
  LINK_LIBRARIES exceptions types vfs tree
)
