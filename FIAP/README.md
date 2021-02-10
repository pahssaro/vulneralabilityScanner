O script é voltado para analise de vulnerabilidade em sites criados em frame works especificos como (Joomla, Wordpress, PrestaShop)

Com base em vulnerabilidades ja conhecidas usamos na maioria das vezes a tentativa brute force embora em Wordpress temos arquivos e scripts para tentar explorar as vulnerabilidades.

Tendo como foco a transformaçao mobile da ferramenta, disponibilizando uma API para consulta e analise remota das vulnerabilidades 


OBS: O objetivo do script é demonstrar as vulnerabilidades comuns por esse motivo o projeto é apenas uma POC.

-------------------------------------

##### Joomla
- [x] [Com Jce            ]('#')
- [x] [Com Jwallpapers    ]('#')
- [x] [Com Jdownloads     ]('#')
- [x] [Com Jdownloads2    ]('#')
- [x] [Com Weblinks       ]('#')
- [x] [Com Fabrik         ]('#')
- [x] [Com Fabrik2        ]('#')
- [x] [Com Jdownloads Index]('#')
- [x] [Com Foxcontact     ]('#')
- [x] [Com Blog           ]('#')
- [x] [Com Users          ]('#')
- [x] [Com Ads Manager    ]('#')
- [x] [Com Sexycontactform]('#')
- [x] [Com Media          ]('#')
- [x] [Mod_simplefileupload]('#')
- [x] [Com Facileforms    ]('#')
- [x] [Com Facileforms    ]('#')
- [x] [Com extplorer      ]('#')

##### Wordpress
- [x] [Simple Ads Manager   ](https://www.exploit-db.com/exploits/36614)
- [x] [InBoundio Marketing  ](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_inboundio_marketing_file_upload) 
- [x] [WPshop eCommerce     ](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_wpshop_ecommerce_file_upload)
- [x] [Synoptic             ](https://cxsecurity.com/issue/WLB-2017030099) 
- [x] [Showbiz Pro          ](https://www.exploit-db.com/exploits/35385) 
- [x] [Job Manager          ](https://www.exploit-db.com/exploits/45031) 
- [x] [Formcraft            ](https://www.exploit-db.com/exploits/30002)
- [x] [PowerZoom            ](http://www.exploit4arab.org/exploits/399)
- [x] [Download Manager     ](https://www.exploit-db.com/exploits/35533)
- [x] [CherryFramework      ](https://www.exploit-db.com/exploits/45896)
- [x] [Catpro               ](https://vulners.com/zdt/1337DAY-ID-20256)
- [x] [Blaze SlideShow      ](https://0day.today/exploits/18500)
- [x] [Wysija-Newsletters   ](https://www.exploit-db.com/exploits/33991)

##### PrestaShop
- [x] [attributewizardpro   ]('#')
- [x] [columnadverts        ]('#')
- [ ] [soopamobile          ]('#')
- [x] [pk_flexmenu          ]('#')
- [x] [pk_vertflexmenu      ]('#')
- [x] [nvn_export_orders    ]('#')
- [x] [megamenu             ]('#')
- [x] [tdpsthemeoptionpanel ]('#')
- [ ] [psmodthemeoptionpanel]('#')
- [x] [masseditproduct      ]('#')
- [ ] [blocktestimonial     ]('#')
- [x] [soopabanners         ]('#')
- [x] [Vtermslideshow       ]('#')
- [x] [simpleslideshow      ]('#')
- [x] [productpageadverts   ]('#')
- [x] [homepageadvertise    ]('#')
- [ ] [homepageadvertise2   ]('#')
- [x] [jro_homepageadvertise]('#')
- [x] [advancedslider       ]('#')
- [x] [cartabandonmentpro   ]('#')
- [x] [cartabandonmentproOld]('#')
- [x] [videostab            ]('#')
- [x] [wg24themeadministration]('#')
- [x] [fieldvmegamenu       ]('#')
- [x] [wdoptionpanel        ]('#')

    
      -u --url              url target
      -D --dorks            search webs with dorks
      -o --output           specify output directory
      -t --timeout          http requests timeout
      -c --cms-info         search cms info[themes,plugins,user,version..]
      -e --exploit          searching vulnerability & run exploits
      -w --web-info         web informations gathering
      -d --domain-info      subdomains informations gathering
      -l, --dork-list       list names of dorks exploits
      -n, --number-page     number page of search engine(Google)
      -p, --ports           ports to scan
      -i, --input           specify domains to scan from an input file 
      --threads             number of threads
      --dns                 dns informations gathering
