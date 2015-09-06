# bangalore-startups [![Build Status](https://travis-ci.org/hemanth/bangalore-startups.svg?branch=master)](https://travis-ci.org/hemanth/bangalore-startups)

> Ever growing list of startups in Bangalore.


## Install

```
$ npm install --save bangalore-startups
```


## Usage

```js
var bangaloreStartups = require('bangalore-startups');

console.log(Object.keys(bangaloreStartups)); // JSON {'name' : 'url'}

/* 
[ '100Marks',
  '123Myhub.com',
  '1POINT2IT.com',
  '29labs',
  '365Build',
  '3dfication',
  '40K Foundation Australia ',
  '47Line',
  '49apps',
  '4R RECYCLING PRIVATE',
  '5tronics',
  '64arts.in',
  '88 Cordials',
  '99atoms',
  '99tests',
  '9amigo.com',
  'A & B Associates',
  'A K S TECHNOLOGIX',
  'ABHIKARTA1',
  'ACCESS STB Labs',
  'AD Ventures',
  'AMC Square Learning',
  'AMRRSolutions dba 66cents',
  'ANCIT CONSULTING',
  'APIfy',
  'APProximity',
  'ARIZEON',
  'ARNAV SOFTWARE TECHNOLOGIES',
  'ASIT ',
  'AW SmartDeals and Solutions',
  'AW Smartdeals and solutions ',
  'AaaS - Autocomplete as a Service',
  'Aadishakti Co',
  'Aapka Painter',
  'Aarvaa',
  'Absimpl ',
  'Acadzone',
  'Acagild',
  'Accrete Globus Technology',
  'ActOnMagic',
  'Action Gunners Technologies',
  'ActivMobs',
  'Active Holiday Company',
  'Ad Documentum',
  'AdNabu',
  'AdWyze',
  'Adaptiz Tech Studios',
  'Adepto Solutions ',
  'Adfortheday Media ',
  'Adhira Export',
  'Adhunt.in',
  'Adroit solutions',
  'AdsHippo',
  'AdsTrak',
  'Advanced Components & Devices',
  'Advanced Millennium Technologies',
  'AdviceGrab',
  'Adwog.com',
  'Adxan',
  'AeroLeads',
  'Againn',
  'Agent technologies s/w',
  'Aindra Systems',
  'Airborne',
  'AiringPods.com',
  'Airlink Wireless',
  'Aisle',
  'Akasa Labs ',
  'Akira Consultancy',
  'Alchemy Counsellors',
  'AllGreen Energy Pte.',
  'Allegianz Solutions',
  'Almabase',
  'AlmostFamous',
  'AlphaBeta Labs',
  'AlphaPackers',
  'Amigohub',
  'Amplyfy Labs',
  'Anitya Information Solutions',
  'AnonyByte',
  'Aoxior Technlogies',
  'Apartment Adda',
  'ApnaCourse',
  'ApnaStock',
  'Aporv',
  'AppBoard',
  'AppCovery',
  'Appdra',
  'Appeti',
  'Applait',
  'Apple Kart Technologies',
  'Applicate IT Solutions Private',
  'Applorein',
  'Appnomic Systems',
  'Apps on Click',
  'Appscrip',
  'Appsterix',
  'Apptotech',
  'Arastan',
  'Arena Cakes',
  'ArenaFlorist',
  'Around.io',
  'Array Storm',
  'ArtPandora',
  'ArtSquare',
  'Artoo',
  'Asimo',
  'Asklepian Technologies',
  'Aspirea Technologies',
  'AssetTrackr',
  'AssociatedIT',
  'Atatva Lifestyle Pvt.',
  'Ather Energy',
  'Atriium',
  'Attribo Technologies ',
  'Auctionful',
  'Aurnate.com',
  'Auto Raja',
  'Autoninja',
  'Autopilot',
  'Axio Biosolutions',
  'AxisRooms',
  'Azzist',
  'BOOSTurSKILLS',
  'BOOVE SOFTWARE',
  'BRSoft-Tech Technologies',
  'BRiTi',
  'BUZZVALVE',
  'Baba Fattoosh',
  'Babajob',
  'Baby Prefers',
  'Bakfy (acquired by CommonFloor)',
  'Bangalore Web zone',
  'BangaloreFlora',
  'BankBazaar Health Insurance',
  'Barterd.in',
  'Bconspot',
  'BeOnTrip',
  'Beaconifi',
  'Beevolve',
  'Belong',
  'Beparwah',
  'Best SEO Service',
  'BestBuilder',
  'Bhoole Bisre Geet',
  'Big Data on Cloud',
  'BigBHK',
  'Bigpaa',
  'BimaCRM',
  'Binox',
  'Biogenesis Health Clustre',
  'BitSocket',
  'Bitzotik',
  'Biz Sciences',
  'BizBol',
  'BizToonz',
  'Black and White Business Solutions ',
  'Black and white business  solution',
  'BlackMonk',
  'Blitzkrieg Technology',
  'BlogBeats',
  'Blowhorn',
  'Bluerace Technologies',
  'Bodhi Professional Solutions Pvt.',
  'BookCab',
  'BookHospitals.com',
  'BookYourGround',
  'Bookmycarservice',
  'BooksNear',
  'Boutline',
  'Boxme',
  'Boxure',
  'BrainGain',
  'Brainwave Education',
  'Brand Jockeying',
  'Brekkie',
  'Bribe A Friend',
  'Bribe Me',
  'BrightApps',
  'BrioTribes Technologies',
  'BrizzTV Media Labs',
  'Bro4u.com',
  'Broadr',
  'Bucketkart Online Services',
  'Budli.in',
  'Bugworks Research',
  'Buttercups',
  'BuyHatke',
  'BuyMilkOnline',
  'Buzzinga',
  'ByteBlazers',
  'Bytecode Computing',
  'C&B Electronics',
  'C42 Engineering',
  'CAN Entrepreneurs',
  'CASEconnect',
  'CHALLIDO',
  'CHIPMONK TECHNOLOGIES PRIVATE',
  'CLOUDLITY',
  'CLUDOC - A Healthcare Network',
  'COGXIO.COM',
  'COMBISTORE',
  'Cachy Graphics',
  'CalLiberate',
  'Caliverse',
  'CallHub',
  'CallTruck',
  'Callur',
  'Campaign -  Unity of Disparate Men',
  'Campus Diaries',
  'Campus Sutra',
  'Cannykart',
  'CanvasJS',
  'Capital Float',
  'Capital Mind',
  'CarStudio.com',
  'Caravan Craft Retail Private',
  'Cardiac Design Labs',
  'Career Confidence',
  'CareerAnna',
  'Carfields',
  'Carmatec IT Solutions Pvt Ltd ',
  'Carrots',
  'Carveniche Technologies ',
  'Cashkumar',
  'CatalanLabs',
  'Catalyst Labs',
  'Celerix Technologies',
  'CereBrahm Innovations',
  'Cetati Cybernetics',
  'Channel Bridge Software Labs',
  'ChaseChat.in',
  'Chatimity',
  'Chauka',
  'Cheerz! Labs',
  'Chekkoo',
  'CherGo Ecommerce (CourseMantra)  ',
  'Cheripo',
  'Chipster',
  'Chocozonia',
  'ChoiceBeat',
  'Chorusplay',
  'ChronicWatch',
  'Chumbak',
  'Ciafo',
  'CinchIT Solutions',
  'Circus Social',
  'Citizengage',
  'Classmint.com',
  'ClearTranscripts',
  'ClickOnCare.com',
  'Client of Roland and Associates US ',
  'Client of Roland and Associates in US',
  'Client of Roland and Associates',
  'Clients of R & A',
  'Cliff',
  'Clik2KNow',
  'Clipboard',
  'Cloud Lending',
  'Cloud2SME',
  'CloudInfi',
  'CloudInfra',
  'Cloudaria',
  'CoSited',
  'Coatom',
  'Cobuy',
  'Cocoon',
  'Code-pal',
  'CodeMonk',
  'Codeflow',
  'Codelearn',
  'Coffee Mug Ideas',
  'Colimetrics Software ',
  'CollPoll',
  'Commercial Office Bangalore',
  'CommonFloor',
  'Communyty',
  'Compassites Software Solutions',
  'Confess',
  'Confession9.com',
  'ConfirmTkt.com',
  'ConnectM Technology Solutions',
  'Connovate Technology',
  'Constapark',
  'Content R Square',
  'Content Yogi Solutions',
  'Convergytics',
  'ConversionMonk',
  'Cooey',
  'CookBoxes',
  'Cookaroo',
  'CoolG Edu',
  'Cooolio Online ',
  'CorPool',
  'Cornea Entertainment Private',
  'Cos(x)',
  'Cosmetix',
  'Cotton Slate',
  'CouponDunia',
  'Crafts N Creations',
  'Craftsvenue',
  'Craftveda Retail ',
  'CrazyAntz Technologies',
  'Creat!st',
  'CreedCap Asia Advisors',
  'CrewCove',
  'CribHere',
  'Crisp Stories',
  'Crispify',
  'Critinno',
  'Cropz',
  'Cubeit',
  'Cubito',
  'Cuepra',
  'Cuiserve',
  'Cumulations Technologies',
  'Cupick',
  'Curehub',
  'Curiositi Learning Solutions',
  'Customer Guru',
  'CustomerRivet',
  'CustomerXPs Software ',
  'CustomerXPs Software Private',
  'Cyberglint',
  'CybrHome',
  'D-Rewards',
  'DESINGERSTUFFS',
  'DGSS',
  'DOCTalk',
  'DW Ventures',
  'DailyNinja',
  'DailyRounds',
  'Dapple',
  'Dark Horse',
  'Dartrr',
  'DataDab',
  'DataWeave',
  'Dazeinfo',
  'Dazo',
  'DealArbor',
  'Dealize.Me',
  'Dealstan',
  'Debatr.me',
  'Deepwind',
  'Dekhio',
  'Dekkoh',
  'DelightCircle',
  'DeltaX',
  'Delyver',
  'DesiKhana',
  'Design Dreams',
  'DesignString',
  'DeveloperOnRent',
  'Devsaran',
  'Dexetra',
  'Dexpro Technologies',
  'Dfy Graviti',
  'Dial2Verify Platform',
  'Dial2Verify',
  'Diet and Lifestyle Consultant',
  'DigiFutura',
  'DigiMark Agency',
  'Digiapes Studios',
  'Digital connect',
  'Dilbole',
  'Dine Media Interactive',
  'Dine-Media',
  'Discount Mantra',
  'Dishcoveri',
  'DoSelect',
  'DocEngage',
  'DocMator',
  'DoctorKePaas',
  'Doctors\' Circle',
  'Domy Innovations Cafe',
  'Doodle Ace Consultants',
  'Dootha',
  'DotMach',
  'DoubleSpring',
  'DrawTyme',
  'Dream Merchants',
  'Drink King',
  'DriveU',
  'Driveline',
  'Dronna',
  'DrumUp',
  'Drwheelz Auto Service',
  'Dubroo',
  'DudeGenie',
  'Dukaandaar',
  'Dumroo',
  'Dutch Door Tech',
  'E2e Solution',
  'E9ine.com',
  'EDALLSYSTEMS',
  'EDUCOART EDUCATION SERVICES',
  'ETHNUS Technologies',
  'EZTolley.com',
  'EZkirana',
  'EarthStartups',
  'Easel Studios',
  'Easy Price',
  'Easy Recognition',
  'EasyAccom Ventures',
  'EasyM2M Technologies',
  'EasyM2M',
  'EatOnGo.in',
  'Eatingly',
  'Eatlandish',
  'Eatlo',
  'Eco Store',
  'EdGE Networks ',
  'EduSupport',
  'Education Startup',
  'Educational Startup',
  'Eduplexus Softsol Private',
  'Edupromise',
  'Eduspace Educational Services',
  'Eezyconnect',
  'Efox (Exchange Fox )',
  'Egigs',
  'Eiris Connect ',
  'Ekeeko Payment Solutions Pvt.',
  'Elanic',
  'Elevenity',
  'Elisium Labs',
  'Elisuim Labs_o',
  'Elite Car Care',
  'ElloInc',
  'Embien Technologies',
  'EmployeeSocial',
  'Enable-D',
  'Enact Systems',
  'Encryptik',
  'EngageDino',
  'English Dost',
  'Ensys labs',
  'Eonmall',
  'Eros Now',
  'Essmart',
  'Etable Services',
  'Eukti Learning Solutions',
  'EventFriendly',
  'Eventifier',
  'EventsHigh',
  'EventzIO',
  'EveryBill',
  'EveryCrave',
  'Evibe',
  'Evnts',
  'Evorubix',
  'Evsdrop Solutions',
  'Exchange OST to PST Converter',
  'ExitIntent.io',
  'Exotel',
  'Expin.me',
  'Explore Mobility',
  'Explorers OutdoorEd',
  'Extentor',
  'FFingo Online Services',
  'FHS IdeaLab',
  'FIUME TECHNOLOGIES PRIVATE',
  'FORMCEPT',
  'FOSEngage',
  'FROG',
  'FTMC',
  'FULL BASKET PROPERTY',
  'Fab Fresh',
  'FabFresh',
  'Fabdial Technologies',
  'Fabrisure',
  'Fairket',
  'Falcon-X: Stealth Mode Startup',
  'Fasmot',
  'Fastura Technologies',
  'Febler',
  'FeedbacQ',
  'Feedoozy',
  'FeetApart Wellness',
  'FilmySphere',
  'Filtr',
  'Finance Train',
  'FindX',
  'FindYogi',
  'Finmoney Zone Financial Services',
  'Finovera',
  'FirstRide.in',
  'FitBlink',
  'FitnessPapa',
  'Fitrrati',
  'Flashdoor',
  'Flatchat',
  'Flo Learning',
  'Floh',
  'Foodie Doodle',
  'Foodiewheel',
  'Foodpad.in',
  'Foodtang',
  'Foodville',
  'Foradian',
  'ForceFulcrum',
  'Fordolly',
  'FortunePay',
  'Forus Health',
  'FosterGem',
  'Fotuuk ',
  'Fractalio Data',
  'Fraggingmonk Technologies',
  'Free Energy ',
  'FreeFi',
  'FreeHOLD360° ',
  'Freelancer HQ',
  'Friendly India',
  'Frrole',
  'FuGenX Technologies',
  'Fuel Media Solutions',
  'Fullerene Solutions and Services ',
  'Fume Group',
  'Fumekart',
  'Fumence',
  'Fungroo',
  'Funterior',
  'Furlenco',
  'Future company ',
  'Fyne.in',
  'GALEA',
  'GROMOR',
  'GTAC',
  'GYMNU ONLINE SERVICES INDIA',
  'GaadiKiService',
  'GameBag.in',
  'Gamecorp',
  'Geekybuddha',
  'Geethanjali SME IT Works Private',
  'GenAuth',
  'General Education',
  'General education',
  'Genevie',
  'Genius Idiots',
  'Genius Techs OPC',
  'Get Beyond Limits',
  'Get Closer',
  'Get2Galaxy',
  'Get2Gate',
  'GetSeated',
  'GetSetHR.com',
  'Ghar360',
  'Gia Technologies',
  'GiftZapp',
  'Giftingnation',
  'Giftingnation.com',
  'GiveHope',
  'Giveme5',
  'Glambberg',
  'Glassic Eyewear',
  'Gleanchips ',
  'Global 3D Labs',
  'Global Quality Services',
  'Global Quant Advisors',
  'Globals',
  'Glowship',
  'GoDeliver',
  'GoKrazee "Discover Yourself"',
  'GoVasool Online Shopping India',
  'Godot Media',
  'Gohired.in',
  'Goodbox',
  'Graspberry Technologies',
  'Great CIO',
  'Green Commerce Solutions',
  'Green Cosmos Energy Solutions',
  'GreenEnergee',
  'GreenQ',
  'Greetude Energy',
  'GrepSlash.com',
  'GrexIt',
  'Gripstreet',
  'GroomBaba',
  'Groovli',
  'Grouphone',
  'Grouptable.com',
  'GrowthHacks',
  'Gudville',
  'GyanLab',
  'Gyfts365',
  'Gymhub.in',
  'Gymmy',
  'HIVE',
  'HM Constructions',
  'HOMER',
  'HYPR',
  'HackAcademy',
  'HackerEarth',
  'Halli Oota',
  'HandsFree Networks',
  'Harbinger Solutions',
  'Harsh Jalan',
  'HasGeek',
  'HashLearn',
  'HashTag technologies',
  'Hashics',
  'Hashupp',
  'Haul Apparel ',
  'Hayagriva Business solutions',
  'Headoutt',
  'HealShip',
  'HealthPlix Technologies',
  'HealthStreet',
  'HealthcareMagic',
  'Healthernet',
  'HealthifyMe',
  'Healthstreet',
  'Healthy Concepts',
  'HealthyBurp',
  'Herdies',
  'HereNow',
  'Highstify Technologies Private',
  'Hike International',
  'Hiode Technologies',
  'Hippocampus Learning Centres',
  'HireHub',
  'Hiree',
  'Hirenodes',
  'HiveMinds ',
  'HiveMinds Innovative Market Solutions ',
  'HiveMinds',
  'HolaBangalore',
  'HolidayIQ',
  'HomeTriangle',
  'Hostmate',
  'Hotel Komfort Suites',
  'Hotelsoft',
  'Houzify',
  'Huddler',
  'Hummingbill',
  'Hungry fox',
  'Hunt Discount',
  'HuntShire ',
  'HuntingMyJob.com',
  'HurricaneViz',
  'Hydra ( name will be changed very soon)',
  'Hykle',
  'I Love DIamonds',
  'I Want Offers',
  'ICareU',
  'ILoveLamps',
  'INKONIQ ',
  'INSPIRE GEC ACADEMY',
  'INSTANT Tech Labs',
  'Idea Labs- Shout ',
  'Ideaphora',
  'Ideophone',
  'IgluLabs Software',
  'Image Editing Services Provider',
  'Immersion Online Services',
  'Imogina Technologies',
  'In2Em Systems',
  'InBoundio',
  'InGrapher',
  'InPhase Technologies Private',
  'InSelfies',
  'India Drivers Network (mGaadi.com)',
  'India Future Society',
  'India Home Health Care',
  'IndiaMums',
  'IndianStage',
  'Infinite Loop',
  'Infoholic Research',
  'InfraEyes',
  'Inktract Solutions ',
  'Inncrypto Technologies',
  'Inneds',
  'Innoberate',
  'Innohub Travels',
  'Innointel Global',
  'Innoventes Technologies',
  'Innowave eVentures',
  'Innoz',
  'Inolyst',
  'Insight Jedi',
  'InstaSafe',
  'Instahealth',
  'Instakash',
  'Instamojo',
  'Instano',
  'Instatown',
  'Institute of Product Leadership',
  'Intellect Application Services',
  'Intellect Application Servuces',
  'Intellic',
  'Intellicane',
  'Interaction One',
  'Interestik',
  'Intutics',
  'InvestigateAndCreate.com',
  'IoTDeX',
  'Isthaka',
  'Ithaka - Experience it All',
  'ItoAll',
  'Itsmycollege',
  'Ittisa',
  'JAG & WYT Solutions',
  'JMJ Technologies',
  'JMR Infotech',
  'JUSTOBITUARY.COM',
  'Jaatakam',
  'Jack of all Threads',
  'Jamhub Software',
  'Jana Care',
  'Jaxl',
  'JeeteyRaho',
  'JetSmart - IndJets India',
  'Jiffstore',
  'Jigyasa The School',
  'JiniLabs',
  'Jive Mathew Pictures',
  'JobsForHer',
  'Jobspinch.com',
  'Jobspire',
  'Jogiv',
  'Jolivi',
  'Joyage',
  'Jumproll Software',
  'Jus Hatched (Tech Co-working space)',
  'Just News - by Vikas Chauhan',
  'Just Ri8',
  'JustLikeNew.in',
  'JustReco',
  'Juststickers',
  'Juzzpa!',
  'KAP Computer Solutions',
  'KLIKPICK Retail',
  'Kadel Labs',
  'Kaiota Wearable Technology',
  'Kalippattam',
  'Kalkitech',
  'Kaltec',
  'Karabi Software ',
  'Karabi Softwares ',
  'KaraokeGarage',
  'KarmaSnap',
  'Karnataka Information Technology Venture Capital Fund',
  'Karyaa',
  'Kasualy',
  'Kavaii Analytics',
  'Kayeura Technologies',
  'Kelly Services',
  'Kengs',
  'Kernel Insights',
  'Kettik',
  'Keyplus',
  'Keysome',
  'Khojio',
  'Kilometer.in',
  'Kitchen 18',
  'Klaus IT Solutions',
  'Klonio',
  'KlubKonnect',
  'Knightmaregamestudio',
  'Knowledge Foundry',
  'Konnectrix Business',
  'Koove',
  'Kotak Urja',
  'KountMoney',
  'Kreeo (i-nable Solutions)',
  'KrisMen RennSport',
  'KrisMen Rennsport',
  'Kritter',
  'Krupa Knowledge Store.Pvt.Ltd.',
  'Krush',
  'Kryptos Mobile',
  'KwikAdd',
  'LMNOP Solutions',
  'LOONYMART',
  'LT Research',
  'LatentPilot',
  'LaunchYard',
  'LayerSquare',
  'Leadify',
  'LeapReap Tech Services Pvt.',
  'Learnyst',
  'Leena Restaurants & Resorts',
  'LegalCrystal',
  'Lending Chaupal',
  'LetsTransport',
  'Letstransport',
  'License Estate',
  'LifeMojo',
  'LightMetrics',
  'Like Intern',
  'Limitless Venture Holdings',
  'LinQMart',
  'LinkMySport',
  'LinkSmart Technologies',
  'LinksAlpha',
  'Literated',
  'Little Eye Labs',
  'LiveChant',
  'Living Stylish ',
  'Livspace',
  'Livspace.com',
  'Loaferr',
  'LoanMeet',
  'LocalEngine',
  'LocalOye',
  'LocalQueen',
  'LocoStop.com',
  'Logicadd Software',
  'LogikAvenue IT Solutions',
  'Logistimo',
  'Lokait',
  'Look Mobility',
  'Lookup',
  'Lukup Media',
  'Lumos Design Technology',
  'LuxeLore',
  'Luxire.com',
  'Lykrary',
  'M/s BEAP INDIA',
  'M1L',
  'MEDICARE',
  'MNN Software',
  'MOONSHOT TECHNOLOGIES PRIVATE',
  'MOWARES',
  'MOZVO',
  'MaaXee',
  'Mad About Digital',
  'Madath.com',
  'Mahek Tripathi',
  'Make It Nicer - Jade Magnet',
  'MakeUber',
  'Makery Labs',
  'Mantis Technologies Pvt.',
  'Manye Technologies',
  'MarkupChop',
  'Marooner',
  'Marriage Broker Auntie',
  'Masala Chai',
  'Matchpoint',
  'MateWing.Net',
  'Matherix',
  'MavenHive',
  'MeDine App',
  'Mebelkart',
  'Mech Mocha Game Studios',
  'Mechanic On Door',
  'MedPac Systems',
  'Medgenome Labs',
  'Medi Assist Healthcare Services',
  'Media Mindz',
  'MediaNearby',
  'Medibox Technologies',
  'Medical Tourism',
  'Medidart Healthcare Services ',
  'Medinfi Healthcare',
  'Medinous',
  'Medly',
  'Medyog',
  'Meghrules',
  'Merakisan',
  'MeritSquad',
  'Mesh India',
  'MeshLabs',
  'Metagan Technologies',
  'MetroSmith',
  'Microland',
  'Milaap Social Ventures',
  'Minance Research',
  'Mind Dots Software Systems',
  'MindPwr Unlimited',
  'Mindkey 180 Degrees',
  'Mindting Software Labs',
  'Minemobile',
  'MinkStock',
  'Minsh',
  'Mintash ',
  'Mirrasys',
  'Mistakopedia',
  'Mistral Solutions',
  'Mittal Clothing Private',
  'Ml outline',
  'MoEngage',
  'Mobapper',
  'Mobcircle',
  'MobiBing- Used Gadgets,Verified & Cheap ',
  'MobiComKit',
  'MobiSir Technologies',
  'MobiSparks',
  'MobiTatva',
  'MobiTexter',
  'MobiTrack Technologies Pvt.',
  'Mobisy',
  'Mobule',
  'Mocept',
  'Momoe Technologies ',
  'Mondovo',
  'Moonfrog Labs',
  'Motherhood India',
  'Motsee',
  'MoveInSync Technology Solutions',
  'Moxiter',
  'Moxtra',
  'Mr Websiter',
  'Mubble Networks',
  'Multi Recruit',
  'Multunus',
  'Munu',
  'Must See India',
  'My Thought App',
  'MyCareerAllies',
  'MyCareerStack',
  'MyComp',
  'MyJersey.com',
  'MyUni',
  'MyWorkspace',
  'Myaddress',
  'Mybuffe',
  'Mygram.me',
  'Myhappyjourney',
  'Myrtle Technologies',
  'Mysk Solutions',
  'NCredibles',
  'NEA-IndoUS Ventures',
  'NEURLABS',
  'NG Options',
  'NGON SOFTLABS',
  'NUTREA',
  'Nalini Networks',
  'Nandana Organic',
  'Nanobi data and analytics',
  'NayaGaadi',
  'Nearpark',
  'Neburu IT Services',
  'NetBramha Studios',
  'Neuron Gym',
  'Nevanta',
  'New Rubric Solutions',
  'New You Hair Clinic',
  'NewsHunt',
  'Nexia Commerce',
  'Nexia Labs',
  'NexiaLabs',
  'NextDrop',
  'NextPurple',
  'Nifty Window',
  'NigMeTa Infotech',
  'Nimble Ventures',
  'Ninjaas',
  'Niramaya',
  'Nivaata Systems',
  'NoBroker',
  'Nomad HQ',
  'Noroc Solutions',
  'NotYetDecided',
  'NovoJuris',
  'Nterprise.IT',
  'NudgeSpot',
  'Nudgespot',
  'Nukkad',
  'NumbersFirst',
  'OM Gurus',
  'OODIO',
  'OPA BUSINESS SOLUTIONS',
  'Ocean heights global developers',
  'OddPod',
  'Oliveboard',
  'Olodum Retail private',
  'OnMobile',
  'Once Again',
  'One3One4',
  'OneCloud Consulting ',
  'OneCloud Consulting',
  'OneDigitalAd',
  'Online Prasad',
  'Online Secretary',
  'OoBI ',
  'Oponion',
  'Oranous Business Transformation Systems',
  'OrderDragon',
  'Orgameta Learning Private Limited ',
  'Organic Kashmir',
  'Oriental Software',
  'Orobind',
  'Ospox ',
  'OutTask Labs',
  'OvionMedia',
  'Owenite',
  'Oye Online Technologies',
  'OyeAuto',
  'Oyeparty',
  'PHOTO-ID',
  'PLUGIN NETWORKS',
  'PM Health And Lifecare',
  'PNP Research Labs',
  'PORTEA',
  'PRIMES',
  'PSToM',
  'Packy',
  'Pacnmuv.com',
  'Padhaaro',
  'Paladion',
  'Parallel Labs',
  'Param People Infotech',
  'Paranoid',
  'Parents D\'Lounge',
  'Passport',
  'PathDoor Medical Solutions',
  'Patient-Help',
  'Patterbuzz',
  'Payd',
  'Peepal Consulting',
  'Pennyful',
  'Pentagon Ad Media',
  'Pepper Talk',
  'PeprisMine',
  'Perapy',
  'Perdix Business Solutions',
  'Phoenix Datasieve Private',
  'Phoenix India',
  'Photo Manipulation Services Provider',
  'Pi Theta Technologies',
  'Pi2 Square',
  'PiFrOp games',
  'PicUp',
  'Pickcel',
  'Pickmaxx',
  'PiddlyBox',
  'PifropGames',
  'Pikkol',
  'Pinder Garden',
  'Pingaala',
  'Pingsure',
  'PinkBlue.in',
  'PipeCast',
  'Plabro',
  'PlanBmatters.com',
  'PlanBuff',
  'PlanMy.Travel',
  'PlannTo',
  'Plash Digital Labs Private',
  'Plash Digital Labs',
  'PlaySimple',
  'Playerify',
  'Playlyfe',
  'Plot.io',
  'Pluggx ',
  'Plustxt',
  'Pocket Khaki',
  'Pollinate Energy',
  'PoolCircle',
  'PoshVine',
  'Position2',
  'Postman',
  'Pot',
  'PowerHouse',
  'Powerupcloud Technologies',
  'Prabhavathi Builders',
  'Pracly',
  'PracticalCoding.in',
  'Practo Technologies',
  'Practo',
  'Pramvi',
  'Pratilipi',
  'Predictive Research',
  'Press31',
  'PriceIQ',
  'Primaseller',
  'Procurement Service India- Tutelam',
  'ProdNote',
  'Prodintel Technologies',
  'Prolore Search Marketing Pvt.',
  'PromptCloud',
  'Psi Phi Labs',
  'Pugmarks.me',
  'Purplista',
  'Purpose publications',
  'Pustaka Digital Media',
  'QSG Technologies Pvt.',
  'Qarth Technologies',
  'Qbeeko Labs',
  'Qikwell ',
  'Qonnect App',
  'QuadMo Solutions',
  'Quantama',
  'QuantumGraph',
  'Quiddle',
  'QuietGrowth',
  'Quizizz',
  'Qupid ',
  'Qurater',
  'Qusec.in',
  'Qyk',
  'R & A',
  'R Technologies',
  'RA Creative Insights',
  'RBW Media',
  'REALiz3D',
  'REConnect Energy',
  'RELON ',
  'REWANGO',
  'RadiantTCO',
  'Radioappa',
  'Rainbow Sculptors Studios',
  'Rainmaker',
  'Raio',
  'Rakshanam Technologies',
  'Rangehills Systems - ShopWithIndia',
  'RarePixel',
  'Reach Billion',
  'ReachU',
  'ReaderDeck',
  'Realm Impex Private',
  'RealtyCompass.com',
  'RecipesNext',
  'Reckone Inventions',
  'RecoSense InfoSolutions',
  'Red Force Labs',
  'Redcastle',
  'Reddonatura',
  'Ref',
  'Refcruit',
  'Relatas',
  'ReleaseMill',
  'ReliaSystem Engineering Solutions',
  'Remotorder.net',
  'RentMyStay',
  'RentSher',
  'Rentop',
  'Reputada',
  'Restokitch',
  'Retale.in',
  'RevLeg',
  'Revamp My Closet',
  'Revenge.io',
  'ReviewGist',
  'ReviewMatters',
  'Revive Adserver Mod',
  'Riches Builder',
  'RideSafe',
  'RideShare',
  'Ridingo',
  'Rightaway',
  'Ripple Sports',
  'Rise for India',
  'Roadrunnr',
  'Robots Alive - Simplified Robotics',
  'RockON Technologies',
  'Rocketium',
  'Roland & Associates',
  'Roland And Associates',
  'Rollio',
  'RooKidsApp',
  'RoppenLabs  (theKarrier)',
  'Rossitek',
  'Roundhop',
  'Ruaha Technology Labs',
  'Ruffpage',
  'Ruins of the Renaissance',
  'RushGuest',
  'S2A Embedded systems',
  'SECURASI',
  'SHOPERK',
  'SIBIA Analytics',
  'SKIITCH',
  'SMACINTEL',
  'SME BackOffice',
  'SMERGERS',
  'SOCIATE NOW',
  'SPEC Invent Electronics',
  'SPEROWARE Technologies',
  'SPM IT Solutions',
  'SSF Consultants',
  'SUTECH SOLUTIONS - Designing the Future',
  'Sabha',
  'SaleFrog.in',
  'SalesBabu Business Solutions Pvt Ltd ',
  'Saltbridge Solutions Private',
  'Sameenu Global Knowledge Services',
  'Samplytics Technologies',
  'Samtana',
  'Sandalwood Partners',
  'Sarang Desai and Associates',
  'Saranyu Technologies',
  'SchoolCom',
  'Schoolexpertz Infocomm Pvt.',
  'ScienceAdda',
  'Scootapp',
  'Scoreoff',
  'Scrapehere',
  'Scrawle',
  'SearchEnabler',
  'Self (not registered as company yet)',
  'Sellerworx',
  'Sensara',
  'Sentropi',
  'Senzible Marketing',
  'Sevame',
  'Seven Lakes Technologies',
  'Seventymm',
  'ShareNSearch',
  'Shareboard',
  'Sharechat',
  'ShieldSquare',
  'Shifteasy',
  'Shifter',
  'ShikshaClub',
  'Shinystar.in',
  'Shopable',
  'Shopalike.in',
  'Shopnama',
  'Shopnix',
  'ShoppersOn',
  'Shoptree',
  'ShoutOut',
  'Shree Venkateshwara photo',
  'Shri Sai Dharshanam Trust',
  'Shrunken Planet',
  'Shuffls',
  'Siblingapp.com',
  'Silicon Florist',
  'Simpa Networks',
  'SimpleLife.in',
  'Simplimetric Consulting',
  'SingleContact',
  'Skaoss',
  'Skelta Software',
  'SkiHi Booking Services Private Limited\t',
  'Skill Venue',
  'SkillSpace.in',
  'SkilledTree',
  'SkippCard',
  'Skyriz',
  'Slashroot Labs',
  'SlimRide',
  'Smallcase',
  'SmartOwner',
  'SmartPract Learning Solutions',
  'SmartRx',
  'Smartdeck',
  'Smarter Biz Technologies',
  'Smartpocket',
  'Smatrx',
  'Smokelift technologies',
  'SnacxBox',
  'SnapKaro',
  'SnapNda',
  'Snapittoday',
  'Snapooh.com',
  'Snapshopr',
  'Snapwiz Edutech',
  'Snapwiz',
  'Snooze',
  'Snow',
  'Social Boat',
  'Social Cutlet',
  'Social Hues',
  'Social Panga',
  'Social games',
  'SocialCity.In',
  'Socioboard Technologies',
  'Socioclean',
  'Sofalizing',
  'SoftUp',
  'Sokratik Technologies Pvt.',
  'Solutions Infini Technologies Pvt.',
  'Solvify',
  'Sonata Software',
  'Sosio ',
  'Spaceyard Ventures',
  'Sparduro',
  'Sparsa Creative Labs',
  'Specadel',
  'Sphericon3D',
  'Spidr',
  'Spincycles.in',
  'Spoonfed.in',
  'SportsTurtle',
  'Sportskeeda',
  'SpotChallenge',
  'Spouseup',
  'Spring Edge',
  'Springfinity Internet Solutions',
  'Springr Technologies Pvt.',
  'Sprout Life Foods',
  'Staffio Resourcing',
  'Stallmart Online Services',
  'Stampact!',
  'Start-up',
  'StartupsFM',
  'StayGlad',
  'StockViz',
  'StorNetware Systems',
  'StoreWalk',
  'Storyberry',
  'Storyboard',
  'StraightMart',
  'Strategic Outsourcing Services',
  'Streamflex',
  'Street Smart Mobile Technolgies Pvt.Ltd',
  'String Wars',
  'Stringo',
  'Structize',
  'Stun-a-Reve Solutions Pvt. Ltd. ',
  'StyleLookup',
  'SubIntent',
  'Success Wealth CFD Trading',
  'Suma pvc pipe fittings',
  'Sumari',
  'Summit PayCom',
  'SunSaluter',
  'Supertext',
  'SupportBee',
  'Supreme Gridtech Pvt. Ltd. ',
  'SureBlood',
  'Swift',
  'Swiggy',
  'Switch',
  'SycliQ Geospatial',
  'Symphony Films',
  'SyncUsUp',
  'Synube Technology Solutions',
  'Synup',
  'T.I.G.E.R Innovations',
  'T.I.G.E.R. Innovations',
  'T20times',
  'TARS',
  'TATSAVIT',
  'TELiBrahma',
  'TEQNirvana Softtech Solutions Pvt.',
  'TEQNirvana Softtech Solutions',
  'TGS RAINBOW ',
  'TIRANSH MOTION PICTURES',
  'TOTEON',
  'TVInfo.in',
  'Ta3s Solutions Private',
  'Tabifi Solutions',
  'TagBug.me',
  'Tagipoo',
  'Tagos Design Innovation ',
  'Tagos',
  'Talent Recruit',
  'TalentBridge Technologies',
  'Talview (formerly Interview Master)',
  'Tangent TechnoLabs',
  'Tansquare',
  'TaskMouse Internet',
  'Taste In Town',
  'Tataatsu Idealabs',
  'Tationem',
  'Tatynerds.com',
  'TaxiForSure',
  'Teabox',
  'Team Techie',
  'TeamChirp',
  'TeamKarma',
  'Tech Labz',
  'Techiemers',
  'Techinformatic Software labs',
  'Technofit Solutions ',
  'Technome',
  'Techspeare',
  'Tedform (Technology Education Platform)',
  'Teescode Fashion Apparels',
  'Teewe',
  'TejaSoft Innovations',
  'Tejas Networks India',
  'Tekno Logix',
  'Telemedrev',
  'Telory',
  'Teritree Technologies',
  'Test Company',
  'Testimonials For',
  'Texmote',
  'Thattva Innovations',
  'The Big Toss',
  'The Byte Cafe',
  'The Catchy',
  'The Dakiya',
  'The Freethinking Club',
  'The Hr Practice',
  'The Media Ant',
  'The Rational Pie Labs',
  'The Score Magazine',
  'The Searchme',
  'The Secret Kart',
  'The Social Buy',
  'The Times of World',
  'The Wedding Company',
  'TheBox',
  'TheHouseMonk',
  'TheSecretKart.com',
  'TheSurpriser Flowers and Gifts to India',
  'TheTechPanda',
  'TheTradeStreet',
  'Theertham',
  'Thinc Loyalty',
  'Thindipotha',
  'Think and Learn',
  'ThinkOut',
  'ThinkVidya',
  'Thinstrokes',
  'Those5days',
  'ThoughtStreamTech Private',
  'Threads',
  'Thrillophilia',
  'Thump.in',
  'Tiffinwale.in',
  'Tikshare.com',
  'Tiny Dreams Studio',
  'Titill',
  'TommyJams',
  'Tomonotomo',
  'Tonbo Imaging',
  'ToneTag',
  'Tookitaki',
  'Toorq Media Services',
  'Tootle',
  'Toptomato.in',
  'Torch',
  'TouchPoint Data Sciences Private',
  'Touchfone Technology',
  'Touchkin',
  'Tower of Pizza',
  'Townista',
  'Trackash',
  'Tracxn',
  'TradersCockpit',
  'Traderscockpit',
  'Translab Technologies',
  'Travel Jar',
  'Travel smarter',
  'Travelder',
  'Traverik',
  'Traverse Outdoor Gear ',
  'Traxoid Automation: RFID | GPS | IoT ',
  'Traxroot  IoT Platform',
  'Treebo',
  'Triad Square InfoSec',
  'Triangle VR',
  'Tridz',
  'Trimbill',
  'TripCovery',
  'TripLaud',
  'TripThirsty',
  'Tripigator',
  'Triveous',
  'Trodly',
  'TrucX',
  'TrueFbFriends',
  'Truefood',
  'Trusted Technology Solutions ',
  'Tsepak Technologies',
  'Tuebora',
  'Tummyummy',
  'TunePatrol',
  'Turisys',
  'Turnaround Innovision',
  'Tutelamtech',
  'TutorVista.com',
  'Tutors On Net',
  'Twaang',
  'Twiddly',
  'Twoc Foundation',
  'Tydy',
  'UTI Ventures',
  'UXfin',
  'UnBuffer',
  'Under A Man',
  'Unicom Consulting Services',
  'Uniheights Interio',
  'Uninstall.io',
  'United Fashion Mart',
  'United Mobile Apps',
  'United fashion Mart',
  'Unocoin',
  'Uolo Technology',
  'Updated Hosting Reviews',
  'UpdatedReviews.in',
  'UpperCrestMatrimony',
  'Uptrip',
  'Uranus Innovation ',
  'Urban Fitness',
  'Urban Ladder',
  'UrbanPro.com',
  'Urbway',
  'VBOOKY.COM',
  'VMC Technologies',
  'VMLogix',
  'Vagupu.com',
  'Valencia Nutrition',
  'Valonia',
  'Valuemart Gold & Jewels ',
  'Vanadium',
  'Varada Fertility',
  'Varcas Interactive',
  'Vartile',
  'Vedantu',
  'Vedhalabs',
  'VegDeliver.com',
  'VendorScale.com',
  'Venkat Mangudi Consulting',
  'Venturesity',
  'Verwe Interactive',
  'Vgulp Software',
  'Vgulp',
  'Viamagus',
  'Vibrant ',
  'Vibrant HR',
  'Vibrantcove',
  'Victorious IT Solutions Private Limited ',
  'Vidadmetrix',
  'Vidgyor',
  'Vidwan Marketing',
  'VidyaSunil & Associates',
  'Violetrays.in',
  'Virallens',
  'Visus International',
  'Vital Labs',
  'Vitesla',
  'Vizury Interactive Solutions',
  'VolFox',
  'Vouloir Technologies (18trendz.com)',
  'Vozeal',
  'WEBarrister',
  'WHAT CART',
  'WWstay',
  'Waltzz',
  'Wanderlust Technologies',
  'Washingtown.in',
  'Watchy Technology',
  'Wawgo Technologies',
  'Wealth intelligence network',
  'Web Hostings India',
  'WebCreators.in',
  'WebNamaste',
  'Weballigator',
  'Webhostingsitesindia',
  'Weblyke ',
  'Webtickr',
  'Webyog',
  'Webzeest Technologies Private',
  'Wedding Okay !',
  'Wedeterna ',
  'Wedeterna',
  'Wedogood',
  'Well Done',
  'WellPoster',
  'WhatsOnRent',
  'WhistleTalk',
  'WhiteOrangeWorks Media Pvt.',
  'Whodat',
  'WhyHang Solutions',
  'WhyNot Innovations Private Limited ',
  'WiSense Technologies Pvt.',
  'Wifinity Technology',
  'Wignite Software',
  'Winni : Celebrate relations',
  'WireCamp Media Factory',
  'Wisely.TV',
  'Wish A Band',
  'Wish Radio',
  'WishApp',
  'Wishary',
  'Wits Solutions',
  'Witworks',
  'WizenWorld',
  'Wolf Frameworks',
  'Wolken Software Private',
  'Womanor',
  'Wonderslate Technologies',
  'Wooplr',
  'Wooqer ',
  'Wooqer',
  'Workbench Projects',
  'WorkoutWolves',
  'Wow Labz',
  'Xarato.com',
  'XceedForce',
  'Xenon Automotive',
  'XfilesPro',
  'Xithi Technologies',
  'Xolo',
  'XploreAR',
  'Xurmo',
  'YTS Solutions ',
  'Yatis Technologies',
  'Yatniti Software',
  'Yellowleg',
  'Yet to create one',
  'YoFloor',
  'Yogatribe',
  'Yogurt Labs',
  'YoungCurrent',
  'Your D.O.S.T',
  'YourCabs',
  'Yovdo',
  'Yulop',
  'Zaang',
  'Zaicus',
  'ZapStitch Technologies',
  'Zapp',
  'Zauba Technologies & Data Services',
  'Zeat.in',
  'Zefo',
  'ZenRadius',
  'Zenify',
  'Zepper',
  'Zerch',
  'Zero-Q',
  'ZiP Rooms ',
  'Zingcash',
  'ZingoHub',
  'ZipCircle ',
  'ZipDial',
  'Ziva Software',
  'Zivame',
  'Zivame.com',
  'Zoflix',
  'ZoloStays',
  'Zoom',
  'ZoomCar India',
  'Zoomcar',
  'Zoomo India',
  'Zootr Sports',
  'ZopNow',
  'Zorsay',
  'Ztocky Technologies',
  'Zubio',
  'Zupit !',
  'Zwant*',
  'Zyoin Web',
  'aakriti',
  'accuGPS',
  'actwitty',
  'agileblaze',
  'akkadbakkad',
  'allFAQS',
  'allMemoirs',
  'allchemist',
  'apply2many.com',
  'aujas networks',
  'awesum.in',
  'babzuj',
  'barter.li',
  'basefolder',
  'benipal',
  'blonkr',
  'bluestone.com',
  'bundl',
  'callproperty.in',
  'chaiwalabhaiya.in',
  'chennaistore',
  'clytics',
  'coTrain',
  'commonfloor.com',
  'commonslot',
  'crowdfundtrips.com',
  'dateIITians (Human Relationships)',
  'dealsfull',
  'decidequick',
  'del2infinity',
  'devmag.io',
  'discover places',
  'dollardoc',
  'drivekool.com',
  'dunzo',
  'eCommerce',
  'ePoise Systems',
  'ediotise',
  'eduladder',
  'enParadigm',
  'epaathsala',
  'etrade services',
  'filr.io',
  'flipClass',
  'foOfys Solutions',
  'folksFreak',
  'fortunepay.in',
  'freekall ',
  'freemunky',
  'galleri5',
  'gallibazaar',
  'gemskart.in',
  'getSquareFeet',
  'giftSomethin\'',
  'givevalu',
  'goHomely',
  'goMowgli',
  'gympik',
  'hashedge',
  'hi4hi',
  'honestcollars',
  'househelp',
  'https://www.PrimeBHK.com',
  'i2w',
  'i7 Networks',
  'iAccept Softwares',
  'iBot.Club',
  'iFuture Robotics',
  'iReff',
  'iSPIRT Foundation',
  'iService',
  'iTiffin',
  'iTraveller.com',
  'iTreatment',
  'iValue Infosolutions',
  'iloho',
  'inkif.com',
  'inquy',
  'intelligent systems and solutions ',
  'intrXn',
  'iqlect',
  'itzfloranmore',
  'ixxam.com',
  'karidho.com',
  'kikbak',
  'knowtide',
  'lifebanale',
  'linqs',
  'mHotspot',
  'mTatva',
  'madscientist',
  'mandii',
  'mealbucket',
  'mithacafe.com',
  'mobileGullak',
  'moneysights',
  'mpeers',
  'muHive',
  'myNoticePeriod.com',
  'mySchoolRank',
  'myblib',
  'mycarevault.com (HelixDNA Technologies)',
  'mygola.com',
  'mywash',
  'nGO',
  'nab.!t',
  'nokyooz',
  'not yet named',
  'nuVizz Software Solutions Pvt.',
  'nufame technologies',
  'nwplyng',
  'oCherish',
  'oasisbus.com',
  'onedollarfortune.com',
  'pCloudy.com',
  'paststat',
  'pikSpeak',
  'psss',
  'refer247',
  'refractify',
  'ridesnap.in',
  'schoolsdaddy.com',
  'secondzz.com',
  'sendit.in',
  'seoindia-solution',
  'shophunk',
  'stocksiq.in',
  'streetdials communications',
  'stringroot',
  'stugether',
  'suhṛt',
  'swapzaar',
  'tafreee',
  'tagzuna',
  'test-aka',
  'theKarrier.com',
  'tile.social',
  'timeforpet online pvt.',
  'timeforpet.com',
  'traffnav',
  'trotez',
  'truefood',
  'tutorialsbuzz',
  'two tails business solutions',
  'uber Diagnostics',
  'urbanbinge.com',
  'vHelp',
  'vaibhav techpro solutions',
  'venuebookingz',
  'webminal',
  'webstream.io',
  'whatfix',
  'yelo',
  'yyyy' ]

*/

```


## License

MIT © [Hemanth.HM](http://h3manth.com)
