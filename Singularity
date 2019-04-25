Bootstrap: docker
From: bids/mrtrix3_connectome

%labels
Author "Sabir"

#########
#%setup
#########

#Downlaod packages
%post
  apt-get -ym update
  apt-get -ym install tcsh
  apt-get -ym install bc

%environment
  export IMAGE_NAME="mrtrix3_fix_v3"

