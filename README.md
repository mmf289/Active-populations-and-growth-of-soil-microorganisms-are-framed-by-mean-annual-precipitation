{\rtf1\ansi\ansicpg1252\cocoartf2639
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fswiss\fcharset0 ArialMT;\f2\fswiss\fcharset0 Arial-ItalicMT;
}
{\colortbl;\red255\green255\blue255;\red26\green26\blue26;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c13333\c13333\c13333;\cssrgb\c100000\c100000\c100000;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 ### MAP & the growth of soil microbes (16S qSIP). \
\
This repo contains code necessary to perform primary qSIP calculations used in \'93Active Populations and the growth of soil microorganisms are framed by mean annual precipitation\'94.\
\
##Experiment overview. \
\
In this experiment we collected soils from three annual grasslands in California that span a rainfall gradient and performed incubations with isotopically \'91heavy\'92 water (H<sub>2</sub><sup>18</sup>O). Microorganisms incorporate <sup>18</sup>O into DNA during genome replication and the amount of isotopic incorporation approximates in situ bacterial growth rates (Schwartz 2007). EAF <sup>18</sub>O  was calculated for each bacterial ASV following the protocol outlined in Hungate et al., 2015.\
\
##Scripts. \
\
* Data_preparation formats 16S seq data and incubation data so that it is compatible with the qSIP pipeline\
* qSIP_calculations performs taxon filtering and computes EAF <sup>18</sub>O for bacterial ASVs at each site.\
\
\
##Citations\
\
\pard\pardeftab720\partightenfactor0

\f1\fs26 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Schwartz, E. (2007). Characterization of growing microorganisms in soil by stable isotope probing with H218O.\'a0
\f2\i Applied and environmental microbiology
\f1\i0 ,\'a0
\f2\i 73
\f1\i0 (8), 2541-2546.    \
\
Hungate, B. A., Mau, R. L., Schwartz, E., Caporaso, J. G., Dijkstra, P., van Gestel, N., ... & Price, L. B. (2015). Quantitative microbial ecology through stable isotope probing.\'a0
\f2\i Applied and environmental microbiology
\f1\i0 ,\'a0
\f2\i 81
\f1\i0 (21), 7570-7581}