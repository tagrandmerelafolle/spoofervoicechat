--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v82=0;while true do if (v82==0) then v19=v0(v3(v30,1,1));return "";end end else local v83=0;local v84;while true do if (v83==0) then v84=v2(v0(v30,16));if v19 then local v99=0;local v100;while true do if (v99==1) then return v100;end if (v99==0) then v100=v5(v84,v19);v19=nil;v99=1;end end else return v84;end break;end end end end);local function v20(v31,v32,v33) if v33 then local v85=(v31/(2^(v32-(620 -(555 + 64)))))%((933 -(857 + (951 -(282 + 595))))^(((v33-1) -(v32-(569 -(367 + 201)))) + (2 -1))) ;return v85-(v85%(2 -1)) ;else local v86=(3 -1)^(v32-(1 + 0)) ;return (((v31%(v86 + v86))>=v86) and 1) or (0 -(1637 -(1523 + 114))) ;end end local function v21() local v34=0 + 0 ;local v35;while true do if (v34==(1 -(117 -(32 + 85)))) then return v35;end if (v34==(1065 -(68 + 997))) then v35=v1(v16,v18,v18);v18=v18 + (1271 -(226 + 1044)) ;v34=4 -3 ;end end end local function v22() local v36,v37=v1(v16,v18,v18 + 1 + 1 );v18=v18 + 2 ;return (v37 * (251 + 5)) + v36 ;end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + (7 -4) );v18=v18 + (6 -2) ;return (v41 * ((30800296 -(67 + 113)) -14022900)) + (v40 * (65886 -(87 + 263))) + (v39 * (188 + 68)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=(7 -5) -1 ;local v45=(v20(v43,1 + 0 ,79 -(26 + 33) ) * ((954 -(802 + 150))^(85 -53))) + v42 ;local v46=v20(v43,21,55 -24 );local v47=((v20(v43,24 + 8 )==(998 -(915 + 82))) and  -(443 -(416 + 26))) or (2 -1) ;if (v46==0) then if (v45==(0 + 0)) then return v47 * (0 -(0 -0)) ;else v46=1188 -(1069 + (556 -(145 + 293))) ;v44=0 -0 ;end elseif (v46==(4477 -2430)) then return ((v45==(0 + 0)) and (v47 * ((1 -0)/((0 -0) + 0)))) or (v47 * NaN) ;end return v8(v47,v46-(1814 -((1854 -(998 + 488)) + 423)) ) * (v44 + (v45/(((2 + 4) -(4 + 0))^(70 -(10 + 8))))) ;end local function v25(v48) local v49;if  not v48 then local v87=772 -(201 + 571) ;while true do if (v87==0) then v48=v23();if (v48==(1138 -(116 + 1022))) then return "";end break;end end end v49=v3(v16,v18,(v18 + v48) -(4 -3) );v18=v18 + v48 ;local v50={};for v65=1 + (0 -0) , #v49 do v50[v65]=v2(v1(v3(v49,v65,v65)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return 0 + 0 ;end)();local v52=(function() return;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();while true do local v67=(function() return 0 + 0 ;end)();while true do if (0==v67) then local v90=(function() return 0;end)();while true do if (v90~=(1 -0)) then else v67=(function() return 1;end)();break;end if (v90==(836 -(660 + 176))) then if ((1 + 1)==v51) then v56[ #"91("]=(function() return v21();end)();for v103= #"!",v23() do local v104=(function() return v21();end)();if (v20(v104, #"[", #"\\")~=(202 -(14 + 188))) then else local v106=(function() return 675 -(534 + 141) ;end)();local v107=(function() return;end)();local v108=(function() return;end)();local v109=(function() return;end)();while true do if (v106==0) then local v120=(function() return 0;end)();local v121=(function() return;end)();while true do if (v120==0) then v121=(function() return 0 + 0 ;end)();while true do if (v121==(0 -0)) then v107=(function() return v20(v104,1 + 1 , #"xxx");end)();v108=(function() return v20(v104, #"0313",6 + 0 );end)();v121=(function() return 1385 -(746 + 638) ;end)();end if ((1 + 0)~=v121) then else v106=(function() return 1 + 0 ;end)();break;end end break;end end end if (v106==1) then v109=(function() return {v22(),v22(),nil,nil};end)();if (v107==(0 -0)) then local v124=(function() return 0 -0 ;end)();local v125=(function() return;end)();while true do if (v124~=(341 -(218 + 123))) then else v125=(function() return 1581 -(1535 + 46) ;end)();while true do if (v125==(0 + 0)) then v109[ #"xxx"]=(function() return v22();end)();v109[ #".dev"]=(function() return v22();end)();break;end end break;end end elseif (v107== #"}") then v109[ #"asd"]=(function() return v23();end)();elseif (v107==(5 -3)) then v109[ #"gha"]=(function() return v23() -((2 + 0)^(3 + 13)) ;end)();elseif (v107~= #"asd") then else local v352=(function() return 0 + 0 ;end)();local v353=(function() return;end)();while true do if (v352==(396 -(115 + 281))) then v353=(function() return 0;end)();while true do if (v353~=(0 -0)) then else v109[ #"asd"]=(function() return v23() -((3 -1)^16) ;end)();v109[ #"xnxx"]=(function() return v22();end)();break;end end break;end end end v106=(function() return 2 + 0 ;end)();end if (v106==3) then if (v20(v108, #"xxx", #"xnx")~= #"}") then else v109[ #"0836"]=(function() return v58[v109[ #"0836"]];end)();end v53[v103]=(function() return v109;end)();break;end if (v106==(4 -2)) then if (v20(v108, #"|", #"~")~= #"[") then else v109[7 -5 ]=(function() return v58[v109[2 + 0 ]];end)();end if (v20(v108,4 -2 ,869 -(550 + 317) )~= #",") then else v109[ #"91("]=(function() return v58[v109[ #"19("]];end)();end v106=(function() return 606 -(268 + 335) ;end)();end end end end for v105= #"}",v23() do v54,v105,v28=(function() return v52(v54,v105,v28);end)();end return v56;end if (v51==(0 -0)) then local v102=(function() return 0 -0 ;end)();while true do if (v102==(291 -(60 + 230))) then v54=(function() return {};end)();v55=(function() return {};end)();v102=(function() return 5 -3 ;end)();end if (v102==(287 -(134 + 151))) then v51=(function() return 1;end)();break;end if (v102==(0 + 0)) then v52=(function() return function(v115,v116,v117) local v118=(function() return 0;end)();local v119=(function() return;end)();while true do if (v118~=(1665 -(970 + 695))) then else v119=(function() return 0;end)();while true do if (v119~=(0 -0)) then else local v288=(function() return 811 -(569 + 242) ;end)();while true do if (v288==(0 -0)) then v115[v116-#"{" ]=(function() return v117();end)();return v115,v116,v117;end end end end break;end end end;end)();v53=(function() return {};end)();v102=(function() return 1 + 0 ;end)();end end end v90=(function() return 1991 -(582 + 1408) ;end)();end end end if ((3 -2)~=v67) then else if (v51~=(1252 -(721 + 530))) then else local v97=(function() return 0;end)();local v98=(function() return;end)();while true do if (v97==(0 -0)) then v98=(function() return 0;end)();while true do if (v98~=(3 -2)) then else v58=(function() return {};end)();for v110= #"~",v57 do local v111=(function() return 0 + 0 ;end)();local v112=(function() return;end)();local v113=(function() return;end)();local v114=(function() return;end)();while true do if (v111==(1825 -(1195 + 629))) then v114=(function() return nil;end)();while true do if (v112==1) then if (v113== #",") then v114=(function() return v21()~=(0 -0) ;end)();elseif (v113==2) then v114=(function() return v24();end)();elseif (v113~= #"-19") then else v114=(function() return v25();end)();end v58[v110]=(function() return v114;end)();break;end if (v112==(700 -(271 + 429))) then v113=(function() return v21();end)();v114=(function() return nil;end)();v112=(function() return 1 + 0 ;end)();end end break;end if (v111==(241 -(187 + 54))) then local v123=(function() return 0;end)();while true do if (v123==1) then v111=(function() return 781 -(162 + 618) ;end)();break;end if (v123==(0 + 0)) then v112=(function() return 0 + 0 ;end)();v113=(function() return nil;end)();v123=(function() return 1;end)();end end end end end v98=(function() return 2;end)();end if (v98==(3 -1)) then v51=(function() return 1 + 1 ;end)();break;end if (v98~=(1171 -(418 + 753))) then else v56=(function() return {v53,v54,nil,v55};end)();v57=(function() return v23();end)();v98=(function() return 1;end)();end end break;end end end break;end end end end local function v29(v59,v60,v61) local v62=v59[1 + 0 ];local v63=v59[(1807 -(1202 + 604)) + 1 ];local v64=v59[3];return function(...) local v68=v62;local v69=v63;local v70=v64;local v71=v27;local v72=1 + 0 ;local v73= -(1 + 0);local v74={};local v75={...};local v76=v12("#",...) -1 ;local v77={};local v78={};for v88=529 -(406 + 123) ,v76 do if ((v88>=v70) or (4682<=4541)) then v74[v88-v70 ]=v75[v88 + (1770 -((5616 -3867) + (32 -12))) ];else v78[v88]=v75[v88 + 1 ];end end local v79=(v76-v70) + 1 + 0 ;local v80;local v81;while true do local v89=1322 -(894 + 355 + 73) ;while true do if (v89==(1 + 0 + 0)) then if (v81<=35) then if (v81<=(1162 -((628 -162) + 679))) then if (v81<=(19 -11)) then if (v81<=(8 -5)) then if (v81<=((467 + 1434) -(106 + 1794))) then if (v81>((0 -0) + 0)) then local v129=0;local v130;while true do if ((0 + (0 -0))==v129) then v130=v80[5 -3 ];do return v13(v78,v130,v73);end break;end end else v78[v80[3 -1 ]]=v61[v80[3]];end elseif (v81>2) then local v133=v69[v80[7 -4 ]];local v134;local v135={};v134=v10({},{__index=function(v231,v232) local v233=v135[v232];return v233[115 -(4 + 110) ][v233[586 -(57 + 527) ]];end,__newindex=function(v234,v235,v236) local v237=v135[v235];v237[1][v237[1429 -(41 + 1386) ]]=v236;end});for v239=104 -((28 -11) + 86) ,v80[4] do v72=v72 + 1 + 0 ;local v240=v68[v72];if (v240[1 -(0 -0) ]==(1306 -(1040 + 243))) then v135[v239-(2 -1) ]={v78,v240[5 -2 ]};else v135[v239-(3 -2) ]={v60,v240[1 + 2 ]};end v77[ #v77 + (1 -0) ]=v135;end v78[v80[67 -(30 + 35) ]]=v29(v133,v134,v61);else v78[v80[2 + 0 ]]=v78[v80[1260 -(1043 + 214) ]]%v78[v80[4]] ;end elseif (v81<=5) then if ((v81>(15 -11)) or (3026>=4046)) then do return;end else v78[v80[2]][v78[v80[1215 -(323 + 889) ]]]=v80[4];end elseif (v81<=6) then v78[v80[5 -3 ]][v80[583 -(349 + 12 + (653 -434)) ]]=v78[v80[324 -((1900 -(559 + 1288)) + 267) ]];elseif (v81==(2 + 5)) then v78[v80[415 -(15 + 348 + 50) ]]=v60[v80[3]];else local v249=0 + 0 ;local v250;local v251;local v252;local v253;while true do if (v249==(2 + 0)) then for v355=v250,v73 do v253=v253 + (983 -(18 + 964)) ;v78[v355]=v251[v253];end break;end if (v249==((10 -7) -2)) then v73=(v252 + v250) -(1 + 0) ;v253=0 + (0 -0) ;v249=852 -(20 + 830) ;end if (v249==(0 + 0)) then v250=v80[128 -(116 + 10) ];v251,v252=v71(v78[v250](v78[v250 + 1 ]));v249=1;end end end elseif (v81<=(1 + 0 + 11)) then if (v81<=(748 -(542 + 196))) then if (v81>(18 -(16 -7))) then v78[v80[1 + 1 ]]=v78[v80[2 + 1 ]]%v78[v80[4]] ;else v78[v80[1 + 1 ]]= #v78[v80[7 -4 ]];end elseif ((2008>638) and (v81>((139 -111) -17))) then v78[v80[2]]=v78[v80[1554 -(1126 + (2336 -(340 + 1571))) ]]%v80[409 -(118 + 287) ] ;elseif (v80[(3 + 4) -(1777 -(1733 + 39)) ]==v78[v80[(3091 -1966) -((1152 -(125 + 909)) + (2951 -(1096 + 852))) ]]) then v72=v72 + (2 -1) ;else v72=v80[380 -(142 + 106 + 129) ];end elseif (v81<=((89 -26) -49)) then if (v81>(3 + 10)) then local v145=v80[979 -(537 + 16 + 424) ];v78[v145]=v78[v145](v13(v78,v145 + (1 -(512 -(409 + 103))) ,v80[3 + (236 -(46 + 190)) ]));else v78[v80[2 + (95 -(51 + 44)) ]]=v78[v80[1 + 2 ]];end elseif (v81<=(9 + 6)) then if (v78[v80[1 + 1 ]]==v80[3 + (1318 -(1114 + 203)) ]) then v72=v72 + (2 -1) ;else v72=v80[7 -4 ];end elseif (v81>(35 -19)) then local v256=v80[1 + 1 ];local v257,v258=v71(v78[v256](v13(v78,v256 + (4 -3) ,v73)));v73=(v258 + v256) -(754 -(239 + 514)) ;local v259=0 + 0 ;for v292=v256,v73 do v259=v259 + 1 ;v78[v292]=v257[v259];end else v78[v80[1331 -(437 + 360 + 532) ]]=v78[v80[3 + 0 ]][v80[2 + 2 ]];end elseif ((1775<=3233) and (v81<=26)) then if (v81<=(49 -28)) then if ((v81<=(1221 -(373 + 829))) or (4543==1997)) then if ((v81==(749 -(476 + 255))) or (3102<728)) then local v149=v80[(2083 -950) -(244 + 125 + 761) ];local v150=v78[v149];for v242=v149 + (727 -(228 + 498)) ,v80[3 + 1 ] do v150=v150   .. v78[v242] ;end v78[v80[2 -0 ]]=v150;else local v152=0;local v153;local v154;local v155;while true do if (v152==0) then v153=v80[3 -1 ];v154=v78[v153];v152=239 -(64 + 174) ;end if ((345==345) and (v152==(1 + 0))) then v155=v78[v153 + ((2 + 0) -0) ];if (v155>(336 -(144 + 192))) then if (v154>v78[v153 + (217 -(42 + 174)) ]) then v72=v80[3];else v78[v153 + 3 ]=v154;end elseif ((v154<v78[v153 + 1 + 0 ]) or (2827<378)) then v72=v80[3];else v78[v153 + 3 + 0 ]=v154;end break;end end end elseif (v81==(9 + 11)) then local v156=v80[1506 -(363 + 820 + 321) ];local v157=v78[v156];local v158=v78[v156 + 2 ];if (v158>(1580 -(1183 + 334 + 63))) then if (v157>v78[v156 + (2 -1) ]) then v72=v80[3 + 0 ];else v78[v156 + 3 + 0 ]=v157;end elseif (v157<v78[v156 + 1 + 0 ]) then v72=v80[(429 + 1549) -((2346 -(153 + 280)) + 62) ];else v78[v156 + 3 ]=v157;end else local v159=v80[2];v78[v159](v13(v78,v159 + 1 ,v80[(5 -3) + 1 ]));end elseif (v81<=(60 -37)) then if ((v81>(1955 -(565 + 1368))) or (3476<2597)) then v78[v80[2]]=v78[v80[11 -8 ]];elseif ((3079<4794) and (v80[2]==v78[v80[1665 -(1477 + 184) ]])) then v72=v72 + ((1 + 0) -0) ;else v72=v80[3];end elseif (v81<=24) then v78[v80[2 + 0 + 0 ]]=v80[859 -(564 + 292) ] + v78[v80[6 -2 ]] ;elseif ((4854>4464) and (v81==(75 -50))) then local v263=304 -(128 + 116 + 60) ;local v264;while true do if (v263==(0 + 0 + 0)) then v264=v80[2];v78[v264]=v78[v264]();break;end end else v78[v80[478 -(41 + 435) ]]=v80[1004 -(938 + 63) ];end elseif ((v81<=30) or (4912==3758)) then if ((126<=3482) and (v81<=(22 + 6))) then if (v81>(1152 -(936 + 189))) then v78[v80[1 + 1 ]]=v80[1616 -(1565 + 48) ];else v78[v80[2]]=v78[v80[2 + 1 ]] + v80[1142 -(782 + 356) ] ;end elseif (v81==(296 -(176 + 51 + 40))) then for v243=v80[4 -2 ],v80[3] do v78[v243]=nil;end else v78[v80[2 -(0 + 0) ]]=v60[v80[1095 -(975 + 117) ]];end elseif (v81<=(1907 -(157 + (2615 -897)))) then if ((v81>(26 + 5)) or (2374==4374)) then local v168=(0 + 0) -0 ;local v169;local v170;local v171;local v172;while true do if (v168==(3 -(669 -(89 + 578)))) then v73=(v171 + v169) -(1019 -(697 + 321)) ;v172=0 -0 ;v168=2;end if (v168==((663 -(174 + 489)) -0)) then v169=v80[4 -2 ];v170,v171=v71(v78[v169](v13(v78,v169 + 1 + 0 ,v80[(12 -7) -2 ])));v168=2 -1 ;end if ((1575==1575) and (v168==(1229 -(322 + 905)))) then for v322=v169,v73 do v172=v172 + (612 -(602 + (1914 -(830 + 1075)))) ;v78[v322]=v170[v172];end break;end end else v78[v80[1191 -(449 + 740) ]]=v78[v80[875 -(591 + 235 + (570 -(303 + 221))) ]]%v80[951 -(245 + 702) ] ;end elseif ((v81<=33) or (2234==1455)) then local v174=0 -0 ;local v175;local v176;local v177;local v178;while true do if ((v174==(1 + 1)) or (1067>1779)) then for v325=v175,v73 do local v326=0 -0 ;while true do if ((2161>=934) and (v326==(1898 -(260 + 1638)))) then v178=v178 + (441 -(382 + 58)) ;v78[v325]=v176[v178];break;end end end break;end if (v174==(3 -2)) then v73=(v177 + v175) -(1 + 0) ;v178=0 -(1049 -(572 + 477)) ;v174=2;end if (v174==(0 -0)) then v175=v80[1207 -(902 + 303) ];v176,v177=v71(v78[v175](v13(v78,v175 + (1 -0) ,v73)));v174=2 -1 ;end end elseif ((1612==1612) and (v81>(3 + 31))) then local v267=1690 -(1121 + 569) ;local v268;local v269;local v270;while true do if (v267==((29 + 186) -(22 + 192))) then v270=v78[v268] + v269 ;v78[v268]=v270;v267=685 -(483 + 200) ;end if ((1463 -(1404 + 59))==v267) then v268=v80[2];v269=v78[v268 + (5 -(1272 -(231 + 1038))) ];v267=1 -0 ;end if ((767 -(468 + 297))==v267) then if (v269>((338 + 224) -(334 + 228))) then if (v270<=v78[v268 + (3 -2) ]) then v72=v80[6 -(3 + 0) ];v78[v268 + ((1 + 4) -2) ]=v270;end elseif (v270>=v78[v268 + (87 -(84 + 2)) ]) then v72=v80[1 + 2 ];v78[v268 + 3 ]=v270;end break;end end else local v271=v80[238 -(141 + 95) ];v78[v271](v13(v78,v271 + (1163 -(171 + 991)) + 0 ,v73));end elseif (v81<=53) then if ((4352>=2833) and (v81<=(112 -(280 -212)))) then if (v81<=(93 -(88 -34))) then if ((v81<=(9 + 28)) or (3222<3073)) then if (v81==(98 -62)) then local v179=v80[(5 -3) + (0 -0) ];v78[v179](v13(v78,v179 + 1 ,v73));elseif  not v78[v80[2 + 0 + 0 ]] then v72=v72 + (1 -0) ;else v72=v80[2 + 1 ];end elseif (v81==38) then local v180=0;local v181;while true do if ((744<=2942) and (v180==0)) then v181=v80[844 -(497 + 345) ];do return v78[v181](v13(v78,v181 + ((574 -410) -(92 + 71)) ,v80[2 + 1 ]));end break;end end else local v182=0 -0 ;local v183;local v184;while true do if ((v182==(0 -0)) or (1833<=1322)) then v183=v80[768 -(574 + (307 -116)) ];v184=v78[v183];v182=1 + 0 ;end if (v182==(2 -1)) then for v327=v183 + 1 ,v80[(9 -6) + 1 ] do v184=v184   .. v78[v327] ;end v78[v80[(2099 -(111 + 1137)) -(254 + 595) ]]=v184;break;end end end elseif (v81<=(167 -(10 + 45 + 71))) then if (v81>40) then local v185=v80[2 -(1333 -(605 + 728)) ];do return v78[v185](v13(v78,v185 + (1791 -(573 + 1217)) ,v80[8 -5 ]));end else local v186=0 + (158 -(91 + 67)) ;local v187;local v188;local v189;local v190;while true do if ((v186==1) or (3467<=1055)) then v73=(v189 + v187) -1 ;v190=0 + 0 ;v186=2 -0 ;end if (v186==2) then for v328=v187,v73 do local v329=939 -(714 + (669 -444)) ;while true do if ((3541==3541) and (v329==0)) then v190=v190 + (2 -(1 + 0)) ;v78[v328]=v188[v190];break;end end end break;end if ((((523 -(423 + 100)) -0)==v186) or (3557>=4003)) then v187=v80[1 + 1 + 0 ];v188,v189=v71(v78[v187](v13(v78,v187 + 1 ,v80[3 -0 ])));v186=807 -(118 + 688) ;end end end elseif (v81<=42) then local v191=48 -((55 -30) + 2 + 21) ;local v192;local v193;local v194;local v195;while true do if (v191==((0 -0) + 0)) then v192=v80[1888 -(927 + 959) ];v193,v194=v71(v78[v192](v78[v192 + 1 + 0 ]));v191=3 -2 ;end if ((733 -(16 + 716))==v191) then v73=(v194 + v192) -1 ;v195=0 -0 ;v191=3 -1 ;end if (v191==((273 -174) -(6 + 5 + 86))) then for v330=v192,v73 do local v331=0 -0 ;while true do if (v331==0) then v195=v195 + (286 -(175 + 110)) ;v78[v330]=v193[v195];break;end end end break;end end elseif (v81==(107 -64)) then v72=v80[14 -(782 -(326 + 445)) ];else do return;end end elseif (v81<=(1844 -(503 + (5642 -4349)))) then if (v81<=((97 + 31) -82)) then if (v81>(33 + (501 -(457 + 32)))) then if (v78[v80[1063 -((1804 -994) + 107 + 144) ]]==v80[4]) then v72=v72 + (1403 -(832 + 570)) + (0 -0) ;else v72=v80[3];end else v78[v80[(712 -(530 + 181)) + (882 -(614 + 267)) ]]={};end elseif ((v81==(41 + 2 + 4)) or (657>=1668)) then local v197=v80[535 -(43 + (522 -(19 + 13))) ];v78[v197](v78[v197 + ((192 + 542) -(711 + 22)) ]);else v78[v80[7 -5 ]][v78[v80[3]]]=v78[v80[863 -(240 + 619) ]];end elseif (v81<=(13 + 37)) then if ((v81==(77 -28)) or (1027>3858)) then local v200=0 + 0 ;local v201;while true do if ((v200==(1744 -(1344 + (1415 -1015)))) or (3654<450)) then v201=v80[407 -(255 + 73 + 77) ];v78[v201]=v78[v201](v13(v78,v201 + 1 + 0 ,v73));break;end end else local v202=v80[2 + (0 -0) ];v78[v202](v13(v78,v202 + (797 -(588 + 208)) ,v80[12 -9 ]));end elseif (v81<=((441 -277) -113)) then v78[v80[1741 -((2204 -(884 + 916)) + (2794 -1459)) ]][v80[409 -((425 -242) + 223) ]]=v78[v80[4 -0 ]];elseif ((1891<4453) and (v81>52)) then if  not v78[v80[2 + 0 ]] then v72=v72 + 1 + 0 ;else v72=v80[340 -(6 + 4 + 327) ];end else for v308=v80[2 + (0 -0) ],v80[656 -(232 + 421) ] do v78[v308]=nil;end end elseif (v81<=(400 -(118 + 220))) then if (v81<=(19 + 38)) then if ((v81<=(504 -(108 + 341))) or (3140<2129)) then if ((v81>(25 + 8 + 21)) or (2555<1240)) then local v205=v80[8 -6 ];v78[v205]=v78[v205](v13(v78,v205 + ((2627 -1133) -(711 + 782)) ,v80[5 -2 ]));else local v207=469 -(270 + 199) ;local v208;local v209;local v210;while true do if (v207==(0 + 0)) then v208=v80[(3776 -1955) -(580 + 1239) ];v209=v78[v208 + (5 -3) ];v207=1;end if (1==v207) then v210=v78[v208] + v209 ;v78[v208]=v210;v207=2 + 0 ;end if ((1 + 1)==v207) then if (v209>(0 + 0)) then if ((v210<=v78[v208 + (2 -1) ]) or (4727<=4722)) then local v370=1812 -(1293 + 519) ;while true do if ((740<4937) and (v370==(0 + 0))) then v72=v80[1170 -(645 + 522) ];v78[v208 + ((440 + 1353) -(1010 + 780)) ]=v210;break;end end end elseif ((3658>=280) and (v210>=v78[v208 + 1 + 0 ])) then v72=v80[14 -11 ];v78[v208 + (8 -5) ]=v210;end break;end end end elseif ((v81==56) or (885>=1031)) then v78[v80[2]]=v78[v80[1839 -(1045 + 791) ]] + v80[9 -5 ] ;else v78[v80[2 -0 ]]={};end elseif ((3554>=525) and (v81<=(564 -((715 -364) + 154)))) then if ((2414<=2972) and (v81>((4260 -2628) -(244 + 1037 + 293)))) then local v213=266 -(28 + 238) ;local v214;local v215;local v216;while true do if ((3529<=3538) and (v213==(6 -4))) then for v333=2 -1 ,v80[(2988 -1425) -(1381 + 178) ] do v72=v72 + 1 + 0 ;local v334=v68[v72];if (v334[1 + 0 ]==(10 + 13)) then v216[v333-(3 -2) ]={v78,v334[3 + 0 ]};else v216[v333-1 ]={v60,v334[1159 -(1074 + 82) ]};end v77[ #v77 + (1 -0) ]=v216;end v78[v80[4 -2 ]]=v29(v214,v215,v61);break;end if ((v213==(1784 -(214 + 1570))) or (2861<458)) then v214=v69[v80[1458 -(990 + 247 + 218) ]];v215=nil;v213=1 + 0 ;end if ((1717<=4525) and (v213==(1 + 0))) then v216={};v215=v10({},{__index=function(v336,v337) local v338=v216[v337];return v338[1 + 0 ][v338[7 -5 ]];end,__newindex=function(v339,v340,v341) local v342=v216[v340];v342[1727 -(1668 + 58) ][v342[628 -(512 + 114) ]]=v341;end});v213=5 -3 ;end end else v72=v80[5 -2 ];end elseif ((v81<=(208 -(7 + 141))) or (3178<=1524)) then local v218=v80[(1454 -(666 + 787)) + (426 -(360 + 65)) ];v78[v218](v78[v218 + 1 + 0 + (254 -(79 + 175)) ]);elseif (v81==(54 + 7)) then v78[v80[2]][v78[v80[3]]]=v78[v80[13 -9 ]];else local v277=v80[1996 -(109 + 1885) ];local v278=v78[v80[1472 -((2000 -731) + 200) ]];v78[v277 + (1 -0) ]=v278;v78[v277]=v278[v80[4]];end elseif (v81<=(881 -(98 + 717))) then if (v81<=(890 -(802 + 24))) then if ((4254>370) and (v81==(108 -45))) then v78[v80[2 -0 ]][v78[v80[1 + 2 ]]]=v80[4];else local v221=v80[4 -2 ];v78[v221]=v78[v221](v13(v78,v221 + 1 + 0 ,v73));end elseif (v81==(3 + 8 + 54)) then v78[v80[1 + 1 ]]=v61[v80[(7 + 1) -5 ]];else v78[v80[2]]=v78[v80[9 -(2 + 4) ]][v80[2 + 2 ]];end elseif (v81<=(28 + 40)) then if (v81==(56 + 11)) then v78[v80[2 + 0 ]]=v80[2 + 1 ] + v78[v80[1437 -(797 + 636) ]] ;else local v228=v80[9 -(21 -14) ];do return v13(v78,v228,v73);end end elseif ((v81<=(1688 -((2747 -1320) + 192))) or (1635==1777)) then local v229=0 + 0 ;local v230;while true do if (v229==(0 -(0 + 0))) then v230=v80[2];v78[v230]=v78[v230]();break;end end elseif ((v81>((1159 -(709 + 387)) + 7)) or (3338>=3993)) then v78[v80[1 + 1 ]]= #v78[v80[(1228 -(503 + 396)) -(192 + 134) ]];else local v283=v80[1278 -(316 + 960) ];local v284=v78[v80[2 + 1 ]];v78[v283 + 1 + 0 ]=v284;v78[v283]=v284[v80[4]];end v72=v72 + (182 -(92 + 89)) + 0 ;break;end if (v89==(1858 -(673 + 1185))) then v80=v68[v72];v81=v80[3 -2 ];v89=552 -((240 -157) + (907 -439)) ;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!A33Q0003063Q00737472696E6703043Q006368617203043Q00627974652Q033Q0073756203053Q0062697433322Q033Q0062697403043Q0062786F7203053Q007461626C6503063Q00636F6E63617403063Q00696E73657274026Q00514003103Q000AA0884FE65A703DBBB249F16F713FAA03073Q00185CCFE12C8319026Q005040030B3Q00F6821FFCB42QD5DEA014EC03073Q00AFBBEB7195D9BC025Q00804F4003043Q007D5759F603083Q006B39362B9D15E6E7026Q004F4003053Q006EC0E05B5F03073Q00E03AA885363A92025Q00804E4003073Q00792361E556495B03063Q00203840139C3A025Q00804D4003043Q00D6476A0F03043Q006A852E10026Q004D4003083Q008AF3C3F533CAA67603083Q001EDE92A1A25AAED2025Q00804C4003093Q00E4DC8D0EE7DCC932A603043Q005D86A5AD026Q004C4003083Q009E6DBBB43AB974BC03053Q0053CD18D9E0026Q004B4003133Q0074DC3AD30242DE75EA0B4ECF309C274FCD219C03053Q006427AC55BC025Q00804A4003053Q0098A00548B303073Q00AFCCC97124D68B025Q0080484003083Q009F004B52ED4FE79F03073Q0080EC653F268421026Q00484003043Q00FD1C08DD03073Q00E6B47F67B3D61C025Q0080474003083Q001681AB580D86162Q03083Q007045E4DF2C64E871026Q00474003053Q0099D404FC7D03063Q0096CDBD709018026Q00464003083Q0029E8ACA4A5B3A00903073Q00C77A8DD8D0CCDD025Q008045402Q033Q008C25CE03053Q0087E14CAD72026Q00454003043Q003833BD3603073Q00497150D2582E57025Q0080444003073Q00F01F8DF8CCC61D03053Q00AAA36FE297026Q00444003053Q000C0796CAAF03053Q00CA586EE2A6026Q00434003043Q00FFE738BC03073Q006BB28651D2C69E025Q00804140030F3Q009EE5CEC1B6FDE8C7AAE0CBD090FCD903043Q00A4D889BB026Q003F4003083Q007C4B172833E41D5603073Q0072383E6549478D026Q003E40031B3Q00E0CCEB1C2QC7FC55C4D0AE54D5D7AE5ED1C1E01CD8CBEF58D1C0A003043Q003CB4A48E026Q003D4003073Q007527512C2050EC03073Q009836483F58453E026Q003C4003063Q0021E2B0CB09FA03043Q00AE678EC5026Q003B4003053Q00FC27348CB103073Q009CA84E40E0D479026Q00344003073Q00F4447F1BBF5E8603063Q007EA7341074D9026Q00324003103Q003119B0280235B12A1325BC39111FBA2E03043Q004B6776D9026Q00304003083Q00A8F13E51FAA688FB03063Q00C7EB90523D98026Q002C40030B3Q0092EC39C80AA723D3BFE62403083Q00A7D6894AAB78CE53026Q002A4003053Q003FDE517D7803083Q00876CAE3E121E1793026Q00284003053Q008FD056511B03053Q007EDBB9223D026Q00224003263Q001DC9259B69D23C8726C7299A69CD299C3A8135873C8139862BC022C83FCE258B2C812F8028D503043Q00E849A14C026Q00204003073Q00E83329F2DBA4DF03063Q00CAAB5C4786BE026Q001C4003123Q0031AA8438DF07A8CB01D60BB98E77FA0ABB9F03053Q00B962DAEB57026Q00184003053Q0088CAC3060703063Q004BDCA3B76A62028Q00026Q000840030A3Q005365744C696272617279026Q00F03F03133Q0049676E6F72655468656D6553652Q74696E6773026Q001040027Q004003073Q004F7074696F6E7303043Q004D61696E030C3Q00412Q6450617261677261706803093Q00412Q6442752Q746F6E034Q00026Q00144003153Q004275696C64496E7465726661636553656374696F6E03083Q0053652Q74696E677303123Q004275696C64436F6E66696753656374696F6E03093Q0053656C65637454616203063Q004E6F7469667903123Q004C6F61644175746F6C6F6164436F6E66696703103Q0053657449676E6F7265496E646578657303093Q00536574466F6C646572031D3Q00466C75656E745363726970744875622F73706563696669632D67616D6503063Q00412Q64546162030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403593Q00682Q7470733A2Q2F7261772E67697468756275736572636F6E74656E742E636F6D2F64617769642D736372697074732F466C75656E742F6D61737465722F412Q646F6E732F496E746572666163654D616E616765722E6C7561030C3Q0043726561746557696E646F7703073Q0056657273696F6E026Q00644003053Q005544696D32030A3Q0066726F6D4F2Q66736574025Q00208240025Q00C07C402Q0103043Q00456E756D03073Q004B6579436F6465030B3Q004C656674436F6E74726F6C030A3Q004765745365727669636503093Q006A6F696E566F69636503493Q00682Q7470733A2Q2F6769746875622E636F6D2F64617769642D736372697074732F466C75656E742F72656C65617365732F6C61746573742F646F776E6C6F61642F6D61696E2E6C756103543Q00682Q7470733A2Q2F7261772E67697468756275736572636F6E74656E742E636F6D2F64617769642D736372697074732F466C75656E742F6D61737465722F412Q646F6E732F536176654D616E616765722E6C75610095013Q00397Q00122Q000100013Q00204200010001000200122Q000200013Q00204200020002000300122Q000300013Q00204200030003000400122Q000400053Q0006350004000B0001000100042B3Q000B000100122Q000400063Q00204200050004000700122Q000600083Q00204200060006000900122Q000700083Q00204200070007000A00063B00083Q000100062Q00173Q00074Q00173Q00014Q00173Q00054Q00173Q00024Q00173Q00034Q00173Q00064Q000D000900083Q00121A000A000C3Q00121A000B000D4Q00370009000B00020010063Q000B00092Q000D000900083Q00121A000A000F3Q00121A000B00104Q00370009000B00020010063Q000E00092Q000D000900083Q00121A000A00123Q00121A000B00134Q00370009000B00020010063Q001100092Q000D000900083Q00121A000A00153Q00121A000B00164Q00370009000B00020010063Q001400092Q000D000900083Q00121A000A00183Q00121A000B00194Q00370009000B00020010063Q001700092Q000D000900083Q00121A000A001B3Q00121A000B001C4Q00370009000B00020010063Q001A00092Q000D000900083Q00121A000A001E3Q00121A000B001F4Q00370009000B00020010063Q001D00092Q000D000900083Q00121A000A00213Q00121A000B00224Q00370009000B00020010063Q002000092Q000D000900083Q00121A000A00243Q00121A000B00254Q00370009000B00020010063Q002300092Q000D000900083Q00121A000A00273Q00121A000B00284Q00370009000B00020010063Q002600092Q000D000900083Q00121A000A002A3Q00121A000B002B4Q00370009000B00020010063Q002900092Q000D000900083Q00121A000A002D3Q00121A000B002E4Q00370009000B00020010063Q002C00092Q000D000900083Q00121A000A00303Q00121A000B00314Q00370009000B00020010063Q002F00092Q000D000900083Q00121A000A00333Q00121A000B00344Q00370009000B00020010063Q003200092Q000D000900083Q00121A000A00363Q00121A000B00374Q00370009000B00020010063Q003500092Q000D000900083Q00121A000A00393Q00121A000B003A4Q00370009000B00020010063Q003800092Q000D000900083Q00121A000A003C3Q00121A000B003D4Q00370009000B00020010063Q003B00092Q000D000900083Q00121A000A003F3Q00121A000B00404Q00370009000B00020010063Q003E00092Q000D000900083Q00121A000A00423Q00121A000B00434Q00370009000B00020010063Q004100092Q000D000900083Q00121A000A00453Q00121A000B00464Q00370009000B00020010063Q004400092Q000D000900083Q00121A000A00483Q00121A000B00494Q00370009000B00020010063Q004700092Q000D000900083Q00121A000A004B3Q00121A000B004C4Q00370009000B00020010063Q004A00092Q000D000900083Q00121A000A004E3Q00121A000B004F4Q00370009000B00020010063Q004D00092Q000D000900083Q00121A000A00513Q00121A000B00524Q00370009000B00020010063Q005000092Q000D000900083Q00121A000A00543Q00121A000B00554Q00370009000B00020010063Q005300092Q000D000900083Q00121A000A00573Q00121A000B00584Q00370009000B00020010063Q005600092Q000D000900083Q00121A000A005A3Q00121A000B005B4Q00370009000B00020010063Q005900092Q000D000900083Q00121A000A005D3Q00121A000B005E4Q00370009000B00020010063Q005C00092Q000D000900083Q00121A000A00603Q00121A000B00614Q00370009000B00020010063Q005F00092Q000D000900083Q00121A000A00633Q00121A000B00644Q00370009000B00020010063Q006200092Q000D000900083Q00121A000A00663Q00121A000B00674Q00370009000B00020010063Q006500092Q000D000900083Q00121A000A00693Q00121A000B006A4Q00370009000B00020010063Q006800092Q000D000900083Q00121A000A006C3Q00121A000B006D4Q00370009000B00020010063Q006B00092Q000D000900083Q00121A000A006F3Q00121A000B00704Q00370009000B00020010063Q006E00092Q000D000900083Q00121A000A00723Q00121A000B00734Q00370009000B00020010063Q007100092Q000D000900083Q00121A000A00753Q00121A000B00764Q00370009000B00020010063Q007400092Q000D000900083Q00121A000A00783Q00121A000B00794Q00370009000B00020010063Q0077000900121A0009007A4Q0034000A000F3Q00260F000900E50001007B00042B3Q00E5000100121A0010007A3Q00260F001000DE0001007A00042B3Q00DE00010020460011000B007C2Q000D0013000A4Q00150011001300010020460011000C007C2Q000D0013000A4Q001500110013000100121A0010007D3Q000E0B007D00D50001001000042B3Q00D500010020460011000B007E2Q002F00110002000100121A0009007F3Q00042B3Q00E5000100042B3Q00D5000100260F000900082Q01008000042B3Q00082Q0100121A0010007A3Q00260F001000F60001007A00042B3Q00F60001002042000F000A00810020420011000E00820020460011001100832Q003900133Q000200204200143Q007700204200153Q00742Q003D00130014001500204200143Q007100204200153Q006E2Q003D0013001400152Q001500110013000100121A0010007D3Q00260F001000E80001007D00042B3Q00E800010020420011000E00820020460011001100842Q003900133Q000300204200143Q006B00204200153Q00682Q003D00130014001500204200143Q006500200400130014008500204200143Q006200063B00150001000100012Q00178Q003D0013001400152Q001500110013000100121A0009007B3Q00042B3Q00082Q0100042B3Q00E8000100260F000900142Q01008600042B3Q00142Q010020460010000C00870020420012000E00882Q00150010001200010020460010000B00890020420012000E00882Q00150010001200010020460010000D008A00121A0012007D4Q001500100012000100121A000900773Q00260F000900242Q01007700042B3Q00242Q010020460010000A008B2Q003900123Q000300204200133Q005900204200143Q00562Q003D00120013001400204200133Q005300204200143Q00502Q003D00120013001400204200133Q004D0020040012001300712Q00150010001200010020460010000B008C2Q002F00100002000100042B3Q00942Q0100260F000900302Q01007F00042B3Q00302Q010020460010000B008D2Q003900126Q00150010001200010020460010000C008E00204200123Q004A2Q00150010001200010020460010000B008E00121A0012008F4Q001500100012000100121A000900863Q00260F0009007A2Q01007D00042B3Q007A2Q0100121A0010007A3Q000E0B007D004F2Q01001000042B3Q004F2Q012Q003900113Q000200204200123Q00470020460013000D00902Q003900153Q000200204200163Q004400204200173Q00412Q003D00150016001700204200163Q003E00204200173Q003B2Q003D0015001600172Q00370013001500022Q003D00110012001300204200123Q00380020460013000D00902Q003900153Q000200204200163Q003500204200173Q00322Q003D00150016001700204200163Q002F00204200173Q002C2Q003D0015001600172Q00370013001500022Q003D0011001200132Q000D000E00113Q00121A000900803Q00042B3Q007A2Q01000E0B007A00332Q01001000042B3Q00332Q0100122Q001100913Q00122Q001200923Q00204600120012009300121A001400944Q0028001200144Q004000113Q00022Q00190011000100022Q000D000C00113Q0020460011000A00952Q003900133Q000700204200143Q002900204200153Q00260020420016000A00962Q00270015001500162Q003D00130014001500204200143Q002300204200153Q00202Q003D00130014001500204200143Q001D00200400130014009700204200143Q001A00122Q001500983Q00204200150015009900121A0016009A3Q00121A0017009B4Q00370015001700022Q003D00130014001500204200143Q001700200400130014009C00204200143Q001400204200153Q00112Q003D00130014001500204200143Q000E00122Q0015009D3Q00204200150015009E00204200150015009F2Q003D0013001400152Q00370011001300022Q000D000D00113Q00121A0010007D3Q00042B3Q00332Q0100260F000900D20001007A00042B3Q00D2000100122Q001000923Q0020460010001000A000204200123Q000B2Q00370010001200020020460010001000A12Q002F00100002000100122Q001000913Q00122Q001100923Q00204600110011009300121A001300A24Q0028001100134Q004000103Q00022Q00190010000100022Q000D000A00103Q00122Q001000913Q00122Q001100923Q00204600110011009300121A001300A34Q0028001100134Q004000103Q00022Q00190010000100022Q000D000B00103Q00121A0009007D3Q00042B3Q00D200012Q00053Q00013Q00023Q00023Q00026Q00F03F026Q00704002264Q003900025Q00121A000300014Q004700045Q00121A000500013Q0004130003002100012Q001E00076Q000D000800024Q001E000900014Q001E000A00024Q001E000B00034Q001E000C00044Q000D000D6Q000D000E00063Q002038000F000600012Q0028000C000F4Q0040000B3Q00022Q001E000C00034Q001E000D00044Q000D000E00014Q0047000F00014Q0002000F0006000F001018000F0001000F2Q0047001000014Q00020010000600100010180010000100100020380010001000012Q0028000D00104Q0011000C6Q0040000A3Q000200200C000A000A00022Q00080009000A4Q002200073Q00010004230003000500012Q001E000300054Q000D000400024Q0026000300044Q000100036Q00053Q00017Q00073Q00028Q0003043Q0067616D65030A3Q0047657453657276696365026Q00324003093Q006A6F696E566F69636503053Q007072696E74026Q00344000113Q00121A3Q00013Q00260F3Q00010001000100042B3Q0001000100122Q000100023Q0020460001000100032Q001E00035Q0020420003000300042Q00370001000300020020460001000100052Q002F00010002000100122Q000100064Q001E00025Q0020420002000200072Q002F00010002000100042B3Q0010000100042B3Q000100012Q00053Q00017Q00",v9(),...);
