# CASvsPAS
Supplementary data for our MS 'When the noise goes on: received sound energy predicts sperm whale responses to both intermittent and continuous navy sonar'

Dataset contains two tables
---------------------------
etab = data frame containing exposure sessions
mtab = data frame containing min-by-min data

Variables definitions
--------------------
Tag_ID = tag deployment identifier
Session = sound exposure session type 
Start_UTC, End_UTC = start and end time in GMT/UTC
Focal = was the whale approached during experiments or not
sfromtot = seconds from tag recording start time
depth_first = first depth measurements in 1-each one-min time bin
depth_mean = average depth measurements over 1-min time bins
pitch_mean = circular mean pitch over 1-min time bins
RC_prop, BUZZ_prop = proportion time regular clicking / buzz clicking in each bin
nBUZZ = number of buzz starts in each bin
SLmax, SPLmax, SELmax = maximum source level, received SPL, and received SEL in each time bin
SPLmax_incr, SELmax_incr = maximum SLmax, SPLmax, SELmax since the start of the session
SPLmax_prev, SELmax_prev, SPLmax_post, SELmax_post, GMOO_tsince, UPAS_tsince = variables defined in Table 2
Lat, Lon = coordinates
Bathy_first = bathymetric depth at tag-on time
solarnoon = hour since solar noon
state = most likely behaviour state
NF_prob, LRS_prob = probability (proportion of posterior samples) non-foraging (NF) active state and layer-restricted search (LRS)
