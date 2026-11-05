# Disk Partition Calculator — Android Device Mockups

আপনার দেওয়া ১০টি স্ক্রিনশট থেকে ১০টি আলাদা Android ফোন মকআপ তৈরি করা হয়েছে।

## ফাইল কোথায়

- `01_Android_Mockups/` — অনুরোধ অনুযায়ী Android ডিভাইস মকআপসহ ১০টি ডিজাইন। প্রতিটি আলাদা JPEG এবং PNG ফাইলে আছে।
- `02_Original_No_Frame/` — ঐ একই ১০টি স্ক্রিনশটের ফ্রেমহীন সংস্করণ, ১০৮০ × ১৯২০ ক্যানভাসে। মূল অনুপাত বজায় রাখতে দুই পাশে স্ক্রিনশটের প্রান্তের রঙের প্যাডিং আছে।
- `Preview_All_10_Designs.jpg` — সব ডিজাইনের একসঙ্গে প্রিভিউ। এই প্রিভিউটি আপলোড করার জন্য নয়।
- `File_Map.csv` — কোন ডিজাইন কোন মূল স্ক্রিনশট থেকে তৈরি হয়েছে তার তালিকা।

## Export specifications

- প্রতিটি একক ডিজাইন: **১০৮০ × ১৯২০ পিক্সেল**, portrait, **৯:১৬**।
- JPEG: RGB, quality 96, no chroma subsampling।
- PNG: 24-bit RGB, **alpha/transparency নেই**।
- প্রতিটি ফাইল ৮ MB-এর অনেক নিচে।
- ফোনের স্ক্রিনের বিষয়বস্তু কাটছাঁট বা অসম অনুপাতে প্রসারিত করা হয়নি। পুরো স্ক্রিনশট সমানুপাতিকভাবে রিসাইজ করা হয়েছে।
- শুধু ফোনের ফ্রেম, সাইড বাটন, ব্ল্যাঙ্ক টপ এরিয়ায় ক্যামেরা হোল, সূক্ষ্ম ছায়া এবং আলাদা ব্যাকগ্রাউন্ড যোগ করা হয়েছে। কোনো বিজ্ঞাপন, রেটিং, ব্যাজ বা প্রচারমূলক লেখা যোগ করা হয়নি।
- মূল ১০টি স্ক্রিনশট ফাইল অপরিবর্তিত আছে।

## ডিজাইনের তালিকা

| নম্বর | ফাইল | বিষয় |
|---|---|---|
| 01 | `01_Calculator` | মূল ক্যালকুলেটর |
| 02 | `02_Windows_Setup` | Windows Setup simulation |
| 03 | `03_Single_Partition_Result` | Single-partition হিসাবের ফল |
| 04 | `04_Split_Disk` | Disk split input |
| 05 | `05_Split_Preview` | Split partition preview |
| 06 | `06_Settings` | Settings ও appearance |
| 07 | `07_Settings_About` | Settings, guide ও about |
| 08 | `08_History` | Conversion history |
| 09 | `09_Dark_Calculator` | Dark-theme calculator |
| 10 | `10_Dark_Split` | Dark-theme split |

প্রতিটি ফাইলের এক্সটেনশন `.jpg` অথবা `.png`। আপলোডের সময় একটি ডিজাইনের যেকোনো একটি ফরম্যাট বেছে নিন; একই ডিজাইনের JPEG ও PNG দুটোই আপলোড করবেন না।

## Play Console-এ ব্যবহার করার আগে

Google Play-এর বর্তমান নির্দেশনায় প্রতি সমর্থিত ডিভাইস ধরনে **সর্বোচ্চ ৮টি স্ক্রিনশট** দেওয়া যায়। এখানে অনুরোধ অনুযায়ী ১০টি ডিজাইন দেওয়া হয়েছে; ফোনের লিস্টিংয়ের জন্য আপনার পছন্দের সর্বোচ্চ ৮টি বেছে নিন। [1](https://support.google.com/googleplay/android-developer/answer/9866151?hl=en)

স্ক্রিনশটের সাধারণ প্রযুক্তিগত সীমা: JPEG অথবা alpha ছাড়া 24-bit PNG; সর্বনিম্ন বাহু ৩২০ px, সর্বোচ্চ বাহু ৩৮৪০ px; বড় বাহু ছোট বাহুর দ্বিগুণের বেশি নয়। এই এক্সপোর্টগুলো সেই সীমার মধ্যে আছে। [1](https://support.google.com/googleplay/android-developer/answer/9866151?hl=en)

**গুরুত্বপূর্ণ:** Google বর্তমানে স্ক্রিনশটে শুধু অ্যাপের ইন্টারফেস দেখাতে এবং ডিভাইস ফ্রেম বা অতিরিক্ত গ্রাফিক্স/ব্যাকগ্রাউন্ড ব্যবহার না করার জোরালো পরামর্শ দেয়। তাই মকআপ ডিজাইনগুলোকে সব প্রচারমূলক ব্যবহারের জন্য স্বয়ংক্রিয়ভাবে অনুমোদিত মনে করবেন না। Store listing-এ ব্যবহারের আগে Console-এর সাম্প্রতিক নির্দেশনা মিলিয়ে নিন; প্রয়োজনে `02_Original_No_Frame/` অথবা রিপোজিটরির মূল স্ক্রিনশট ব্যবহার করুন। [1](https://support.google.com/googleplay/android-developer/answer/9866151?hl=en)

এগুলো ফোনের portrait screenshot export; tablet, Chromebook বা feature graphic-এর আলাদা মাপের অ্যাসেট নয়।
