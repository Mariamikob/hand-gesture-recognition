## Open CV
Open CV (Open Source Computer Vision Library) არის ბიბლიოთეკა, რომელიც მეტწილად
ორიენტირებულია რეალური დროის კომპიუტერის ხედვაზე. ის უფასოა როგორც
აკადემიური ასევე კომერციული გამოყენებისთვის. მას აქვს C++,C, Python and Java
ინტერფეისი და მხარს უჭერს Windows-ს, Linux-ს, Mac OS-ს, IOS-სა და Andorid-ს. OpenCV
შემუშავდა ეფექტური გამოთვლისთვის და განსაკუთრებული ყურადღება
გამახვილებულია რეალური დროის პროგრამებზე. ბიბლიოთეკას აქვს 2500-ზე მეტი
გაუმჯობესებული ალგორითმი, რომელიც შეიცავს ყოვლისმომცველ ნაკრებს როგორც
კლასიკურ, ასევე თანამედროვე ტექნოლოგიების ხედვასა და მექანიზმის სწავლების
ალგორითმებს. იგი უზრუნველყოფს ძირითადი მონაცემების სტრუქტურას
გამოსახულების დამუშავებისთვის ეფექტური ოპტიმიზაციით.

## Hand gesture recognition - ხელის ჟესტიკულაციის ამოცნობა
ხელის ჟესტიკულაციის ამოცნობა ძალზედ მნიშვნელოვანია ადამიანის კომპიუტერთან
ურთიერთობისთვის. ბოლო ათწლეულების განმავლობაში, კლავიატურა და მაუსი
მნიშვნელოვან როლს თამაშობენ იმისათვის, რომ კომპიუტერი ადვილად გამოსაყენებელი
გახადონ ადამიანისათვის. ამასთან, ტექნიკისა და პროგრამული უზრუნველყოფის
სწრაფი განვითარების გამო საჭიროა HCI (Human-Computer Interaciton, ადამიანისა და
კომპიუტერის ურთიერთქმედების) ახალი ტიპები. კერძოდ, ტექნოლოგიები, როგორიცაა
მეტყველებისა და ჟესტების ამომცნობი, რომლებიც დიდ ყურადღებას იქცევენ HCI
სფეროში.

ჟესტი ფიზიკური ქცევის ან ემოციების გამოხატვის სიმბოლოა. იგი მოიცავს სხეულისა და
ხელის ჟესტებს. მასში შედის ორი კატეგორია: სტატიკური ჟესტი და დინამიკური ჟესტი.
პირველისთვის სხეულის პოზა ან ხელის მოძრაობა გვაძლევს ნიშანს. ხოლო უკანასკნელი,
სხეულის ან ხელის მოძრაობა გარკვეულ მესიჯებს გადმოგვცემს. ჟესტიკულაცია
შესაძლებელია გამოყენებულ იქნას, როგორც ადამიანისა და კომპიუტერს შორის
კომუნიკაციის საშუალებად. ჟესტის ამომცნობი განსაზღვრავს მომხმარებლის განზრახვას
სხეულის ან სხეულის ნაწილების მოძრაობის ან გადაადგილების გზით. ბოლო
ათწლეულების განმავლობაში მრავალი მკვლევარი ცდილობდა ხელი შეეწყო ხელის
ჟესტების ამოცნობის ტექნოლოგიის გაუმჯობესებისთვის. ხელის ჟესტის ამომცნობი
ძალიან მნიშვნელოვანი და ფასეულია ბევრი აპლიკაციისთვის.

## Hand Segmentation - ხელის სეგმენტაცია
ამ ალგორითმში, ხელის სეგმენტაცია გამოიყენება ხელის გამოსახულების ფონისგან
გამოსაყოფად. არსებობს სეგმენტაციის რამდენიმე მეთოდი. სეგმენტაციაში
მნიშვნელოვანი ნაბიჯია ტრანსფორმაცია და thresholding (მარტივი მეთოდი სურათის
სეგმენტაციისთვის. ნაცრისფერი შკალის სურათიდან, thresholding გამოიყენება
ბინარული (გაორმაგებული) სურათის შესაქმნელად). სეგმენტური ტიხრები გამოსახულია
გარკვეულ რეგიონში, რომლებიც შეიცავს თითოეულ პიქსელს მსგავსი ატრიბუტებით. ამ
ალგორითმში არის კამერის მიერ გადაღებული BGR (Blue Green Red) სურათი, რომელიც
განიხილება როგორც ალგორითმში შენატანი. BGR სურათი გადაკეთებულ იქნა
ნაცრისფერი მასშტაბის სურათად. ნაცრისფერი მასშტაბის სურათი ბუნდოვანია რათა
მივიღოთ ზუსტი კონტური. ბუნდოვანი სურათი კონკრეტული მნიშვნელობის ბარიერია.

## Hand Detection - ხელის ამოცნობა
### Contours - კონტურები
კონტურები არის მრუდები, რომლებიც უერთდებიან ყველა უწყვეტ წერტილს საზღვრის
გასწვრივ, იგივე ფერისა და ინტენსივობის მქონეებს. კონტურირება სასარგებლო
ინსტრუმენტია ფორმის ანალიზისა და ობიექტის გამოვლენა, აღმოჩენისთვის.
### Convex Hull - ამოზნექილი კორპუსი
ამოზნექილი კორპუსი არის უწყვეტი წერილების ნაკრები ევკლიდურ სივრცეში( სივრცე,
რომლის თვისებებს ევკლიდეს აქსიომებით აღწერენ), რომელიც უკავშირდება
კონტურებს. ამოზნექილი კორპუსი დახაზულია კონტურის გარშემო. ის მუშაობს
როგორც გარეკანი ხელის გარშემო.
### Convexity Defects - კონვექსის დეფექტები
როდესაც ამოზნექილი კორპუსი დახატულია ხელის კონტურის გარშემო, ის შეესაბამება
ხელის კონტურის წერტილებს კორპუსის გარეშე. ის გამოიყენებს მინიმალურ წერტილებს
რომ შეავსოს კორპუსი, რათა მოიცვას კონტურის ყველა წერტილი შიგნიდან და
შეინარჩუნოს კონვექსის საკუთრება. ეს იწვევს დეფექტების ფორმირებას ამოზნექილ
კორპუსში (Convex Hull-ში) ,რაც ეხება კონტურს, რომელითაც შედგენილია ხელი.

## Finger Count - თითების დათვლა
ამ მეთოდის მიხედვით, თითების რაოდენობა სხეულის ენაში განისაზღვრება დეფექტის
რაოდენობის მიხედვით ხელის მოძრაობაში.

## სირთულეები

- მუშა/ადვილად გასაგები, დახვეწილი კოდის მოძიება
    - კოდი, რომელიც თანხვედრაში არაა PEP8 style guide-თან, შესაბამისად რთულია კოდის აღქმა და გარჩევა
    - კოდი, რომელიც არ ეშვება სხვადასხვა error-ის გამო
    - Hand Gesture Detection-ის პრინციპების არასრულყოფილი იმპლემენტაცია
- პროგრამის გარე განათებაზე დამოკიდებულება. განათების ცვლილება მნიშვნელოვნად ცვლის პროგრამის შედეგს და ხშირ შემთხვევაში არასტაბილურს ხდის.
