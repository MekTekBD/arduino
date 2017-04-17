[\#আরডুইনো\_২](https://web.facebook.com/hashtag/%E0%A6%86%E0%A6%B0%E0%A6%A1%E0%A7%81%E0%A6%87%E0%A6%A8%E0%A7%8B_%E0%A7%A8?source=feed_text&story_id=1373212566089352)  
 আরডুইন আইডিইঃ  
 আরডুইনো বোর্ডে কোড আপলোড ও ডাটা আদান প্রাদানের জন্যে রয়েছে আরডুইনোর ফ্রি সফটওয়্যার যেটি সরাসরি আরডুইনোর অফিসিয়াল সাইট থেকে নামানো যাবে। যদি ভালো ইন্টারনেট সংযোগ থাকে তাহলে চাইলে আরডুইনো ওয়েব এডিটর ব্যবহার করেও কোডিং করা যাবে। নিচের লিংক থেকে আরডুইনো আইডিইটি নামানো যাবে বা ওয়েব এডিটর দিয়ে কাজ করা যাবে।  
[https://www.arduino.cc/en/main/software](https://www.arduino.cc/en/main/software)  
 সফটওয়্যারটি ইন্সটল করার পর কিছু জিনিস জেনে নেয়া দরকার। 

[![](https://scontent.fdac1-1.fna.fbcdn.net/v/t1.0-0/s480x480/17309040_1373212566089352_2760788532695876912_n.png?_nc_eui2=v1%3AAeFdhEyY89qlUol7z3fdytKBkoRS0A1y1Yz1365T61LtZs_4NSxmFxtU81jmYGiz6hBl5g1rZz2QM8O86OzZ_4UzCx26QLQ1Q7yQq_vyvdN1Xg&oh=5d5ca57c6799bdf8f3d1435e46e0e40b&oe=599AA3B7 "No automatic alt text available.")](https://web.facebook.com/MekTekBD/photos/a.1362379693839306.1073741826.1213521965391747/1373212566089352/?type=3)

প্রথমেই “Tools” অপশনটিতে গেলে দেখা যাবে “Board”, “Port” এবং “Programmer” এই তিনটি অপশন। আরডুইনোর অনেক রকম বোর্ড পাওয়া যায়। এর মধ্যে আরডুইনো উনো, ন্যানো, মেগা এগুলো বেশি ব্যবহৃত, “Board” অপশনে যেয়ে কোন বোর্ডটি ব্যবহার করছি সেটা সিলেক্ট করে দিতে হবে। আরডুইনো বোর্ডে যেহেতু কম্পিউটারের সাথে কন্টোলারের কমিউনিকেশনের জন্য Serial to USB চিপ থাকে তাই আরডুইনো বোর্ডট সরাসরি USB তে কানেক্ট করা যাবে। আরডুইনোতে সফটওয়্যার প্যাকেজে ড্রাইভার দেয়া থাকে, তবে আরফিসিয়্যার কিছু আরডুইনো বোর্ডে কম্পিউটারের সাথে ইন্টারফেসিং এর জন্য আলাদা কোনো চিপ থাকলে সেটা দেখে নিয়ে নেট থেকে ড্রাইভার নামিয়ে ইন্সটল করা যাবে। আরডুইনো ইন্সটলার দিয়ে ইন্সটল না করে ব্যবহার করলেও ড্রাইভার নিজে থেকে ইন্সটল দিয়ে নিতে হবে। এরজন্যে আরডুইনোর ডিরেকটরি ফোল্ডারে যেয়ে “drivers” নামক ফোল্ডারটির ভেতর ডাউনলোড করা ফাইল/ফোল্ডারটি পেস্ট করতে হবে। এরপর ডেক্সটপের “My computer/This PC” তে রাইট ক্লিক করে ম্যানাজ, তারপর ডিভাইস ম্যানাজারে গেলে দেখা যাবে “Ports” অপশনে “Arduino Uno\(COMx\)” এরকম দেখাবে। নাহলে “Other devices” অপশনে “Unknown devices” খুঁজে বের করতে হবে। এরপর রাইট ক্লিক করে “Update driver software”  “Browse my computer for Driver software” এ ক্লিক করে আরডুইনোর ড্রাইভার ফোল্ডার ডিরেক্টরিটি সিলেক্ট করতে হবে। তাহলেই ড্রাইভার ইন্সটলেশন কমপ্লিট হবে। এরপর আসি “Port” অপশনে। ড্রাইভার ইন্সটল দেবার সময় “Device manager” এর “Ports” অপশনে আরডুইনোর পাশে COM6/COM7 এরকম লেখা থাকে। যদি “Port” অপশনে একাধিক পোর্ট দেখায় তাহলে ওখান থেকে দেখে এসে সঠিক পোর্টটি সিলেক্ট করতে হবে। সবশেষে, “Programmer” হিসেবে “AVRISP mkll” select করতে হবে। তাহলেই মোটামুটি কোডিং করার জন্য সফটওয়্যারটি রেডি। তবে বিভিন্ন ডিভাইস বা সেন্সর আরডুইনো দিয়ে চালাতে গেলে “library” এর দরকার পড়ে। আরডুইনোতে ডিফল্ট অনেকগুলো library দেয়া আছে। না দেয়া থাকলে “Sketch”  “Include library”  “library manager” এ যেয়ে library নামানো যাবে, অথবা ইন্টারনেট থেকে নামিয়ে ফাইলটি আরডুইনোর ডিরেক্টরির ভেতর “library” নামক ফোল্ডারে পেস্ট করে দিতে হবে। আরডুইনো ওপেন করলে আরডুইনোর এডিটর উইনডোটি ওপেন হবে, যেখানে আরডুইনো ল্যাংগুয়েজ দিয়ে কোড করতে হবে। এর তিনটি অংশ আছে, “Structure”, “values\(variables and constants\)” এবং “function”. নিচে এগুলোর লিস্ট দেয়া হলো। পরবর্তী কাজে এগুলোরই ব্যবহার হবে, তাই এগুলো সম্পর্কে ভালো ধারনা রাখতে হবে।

 Structure  
 • setup\(\)  
 • loop\(\)

 Control Structures  
 • if  
 • if...else  
 • for  
 • switch case  
 • while  
 • do... while  
 • break  
 • continue  
 • return  
 • goto

 Further Syntax  
 • ; \(semicolon\)  
 • {} \(curly braces\)  
 • // \(single line comment\)  
 • /\* \*/ \(multi-line comment\)  
 • \# define  
 • \# include

 Arithmetic Operators  
 • = \(assignment operator\)  
 • + \(addition\)  
 • - \(subtraction\)  
 • \* \(multiplication\)  
 • / \(division\)  
 • % \(modulo\)

 Comparison Operators  
 • == \(equal to\)  
 • != \(not equal to\)  
 • &lt; \(less than\)  
 • &gt; \(greater than\)  
 • &lt;= \(less than or equal to\)  
 • &gt;= \(greater than or equal to\)

 Boolean Operators  
 • && \(and\)  
 • \|\| \(or\)  
 • ! \(not\)

 Pointer Access Operators  
 • \* dereference operator  
 • & reference operator

 Bitwise Operators  
 • & \(bitwise and\)  
 • \| \(bitwise or\)  
 • ^ \(bitwise xor\)  
 • ~ \(bitwise not\)  
 • &lt;&lt; \(bitshift left\)  
 • &gt;&gt; \(bitshift right\)

 Compound Operators  
 • ++ \(increment\)  
 • -- \(decrement\)  
 • += \(compound addition\)  
 • -= \(compound subtraction\)  
 • \*= \(compound multiplication\)  
 • /= \(compound division\)  
 • %= \(compound modulo\)  
 • &= \(compound bitwise and\)  
 • \|= \(compound bitwise or\)

 Variables  
 Constants  
 • HIGH \| LOW  
 • INPUT \| OUTPUT \| INPUT\_PULLUP  
 • LED\_BUILTIN  
 • true \| false  
 • integer constants  
 • floating point constants

 Data Types  
 • void  
 • boolean  
 • char  
 • unsigned char  
 • byte  
 • int  
 • unsigned int  
 • word  
 • long  
 • unsigned long  
 • short  
 • float  
 • double  
 • string - char array  
 • String - object  
 • array

 Conversion  
 • char\(\)  
 • byte\(\)  
 • int\(\)  
 • word\(\)  
 • long\(\)  
 • float\(\)

 Variable Scope & Qualifiers  
 • variable scope  
 • static  
 • volatile  
 • const  
 Utilities  
 • sizeof\(\)  
 • PROGMEM

 Functions  
 Digital I/O  
 • pinMode\(\)  
 • digitalWrite\(\)  
 • digitalRead\(\)  
 Analog I/O  
 • analogReference\(\)  
 • analogRead\(\)  
 • analogWrite\(\) - PWM

 Due & Zero only  
 • analogReadResolution\(\)  
 • analogWriteResolution\(\)

 Advanced I/O  
 • tone\(\)  
 • noTone\(\)  
 • shiftOut\(\)  
 • shiftIn\(\)  
 • pulseIn\(\)

 Time  
 • millis\(\)  
 • micros\(\)  
 • delay\(\)  
 • delayMicroseconds\(\)

 Math  
 • min\(\)  
 • max\(\)  
 • abs\(\)  
 • constrain\(\)  
 • map\(\)  
 • pow\(\)  
 • sqrt\(\)

 Trigonometry  
 • sin\(\)  
 • cos\(\)  
 • tan\(\)

 Characters  
 • isAlphaNumeric\(\)  
 • isAlpha\(\)  
 • isAscii\(\)  
 • isWhitespace\(\)  
 • isControl\(\)  
 • isDigit\(\)  
 • isGraph\(\)  
 • isLowerCase\(\)  
 • isPrintable\(\)  
 • isPunct\(\)  
 • isSpace\(\)  
 • isUpperCase\(\)  
 • isHexadecimalDigit\(\)

 Random Numbers  
 • randomSeed\(\)  
 • random\(\)

 Bits and Bytes  
 • lowByte\(\)  
 • highByte\(\)  
 • bitRead\(\)  
 • bitWrite\(\)  
 • bitSet\(\)  
 • bitClear\(\)  
 • bit\(\)

 External Interrupts  
 • attachInterrupt\(\)  
 • detachInterrupt\(\)

 Interrupts  
 • interrupts\(\)  
 • noInterrupts\(\)

 Communication  
 • Serial  
 • Stream

 USB \(32u4 based boards and Due/Zero only\)  
 • Keyboard  
 • Mouse

 একে একে এগুলো সম্পর্কে বলা হবে। আরডুইনো করবার আগে C এবং C++ এর ব্যাসিক ধারনা থাকা প্রয়োজন।



