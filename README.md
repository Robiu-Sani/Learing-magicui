# Magic UI

- [components](https://magicui.design/docs/components/marquee)

**Magic UI** হল একটি ইউআই লাইব্রেরি যা বিভিন্ন ইফেক্ট এবং ইউআই উপাদান যোগ করার সুবিধা দেয়। এটি আপনার ওয়েবসাইটকে আরো আকর্ষণীয় এবং প্রফেশনাল করে তুলতে সাহায্য করবে।

## Magic UI এর সুবিধাসমূহ

- **সহজ ইনস্টলেশন ও কনফিগারেশন**: Magic UI খুব সহজেই React এবং Next.js প্রজেক্টে ইনস্টল করা যায় এবং খুব কম কনফিগারেশন প্রয়োজন হয়।
  
- **বিভিন্ন ইফেক্টের সমাহার**: Magic UI অনেক ধরনের প্রি-বিল্ট ইফেক্ট নিয়ে আসে, যেমন: `fade-in`, `slide-up`, `rotate`, `zoom-in`, ইত্যাদি। এগুলো ব্যবহার করে আপনি আপনার ওয়েবসাইটকে আরো আকর্ষণীয় করে তুলতে পারেন।
  
- **Responsive Design**: Magic UI এর ইফেক্টগুলো পুরোপুরি responsive, যা মোবাইল, ট্যাবলেট, এবং ডেস্কটপের জন্য উপযোগী।
  
- **কাস্টমাইজেশন**: আপনি Magic UI এর প্রতিটি উপাদান ও ইফেক্টকে নিজের প্রয়োজন অনুযায়ী কাস্টমাইজ করতে পারেন, যা আপনাকে ফ্লেক্সিবিলিটি দেয়।
  
- **দ্রুত ডেভেলপমেন্ট**: Magic UI ব্যবহারের মাধ্যমে আপনাকে কম কোড লিখতে হয়, ফলে ডেভেলপমেন্ট সময় কমে যায় এবং আপনি দ্রুত প্রজেক্ট ডেলিভারি করতে পারেন।
  
- **প্রফেশনাল এবং আধুনিক ইউআই**: Magic UI ব্যবহার করে আপনার ওয়েবসাইটে প্রফেশনাল এবং আধুনিক ইউআই ডিজাইন করা সম্ভব, যা ইউজারদের আকৃষ্ট করে।
  
- **সম্পূর্ণ ডকুমেন্টেশন**: Magic UI এর সাথে বিস্তারিত ডকুমেন্টেশন প্রদান করা হয়, যা নতুন ব্যবহারকারীদের জন্য অত্যন্ত সহায়ক।

এই সুবিধাগুলো Magic UI কে একটি শক্তিশালী এবং উপযোগী ইউআই লাইব্রেরি হিসেবে প্রতিষ্ঠিত করেছে, যা যেকোনো ধরনের ওয়েবসাইট ডেভেলপমেন্টের জন্য উপযুক্ত।

## ইনস্টলেশন

Magic UI ইন্সটল করতে আপনি নিচের স্টেপগুলি অনুসরণ করতে পারেন।

### React.js এর জন্য

```bash
npm install tailwindcss@latest clsx tailwind-merge framer-motion
```
// lib/utils.ts
```bash
import clsx, { ClassValue } from "clsx";
import { twMerge } from "tailwind-merge";
 
export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs));
}
```
### Next.js এর জন্য

```bash
npx create-next-app@latest
```
What is your project named? my-app <br/>
Would you like to use TypeScript? No / Yes <br/>
Would you like to use ESLint? No / Yes <br/>
Would you like to use Tailwind CSS? No / Yes <br/>
Would you like to use `src/` directory? No / Yes <br/>
Would you like to use App Router? (recommended) No / Yes <br/>
Would you like to customize the default import alias (@/*)? No / Yes <br/>
What import alias would you like configured? @/* <br/>
```base
npx magicui-cli init
```
Which style would you like to use? » Default <br/>
Which color would you like to use as base color? » Slate <br/>
Would you like to use CSS variables for colors? ... no / yes  <br/>

## Some Effects Name

- **Interactive Icon Cloud**: একটি ইন্টারেক্টিভ আইকন ক্লাউড যা মাউসের সাথে ইন্টারঅ্যাক্ট করে।
- **Meteors**: একটি চলন্ত মেটিয়র ইফেক্ট যা ওয়েবপেজে ডাইনামিক এনিমেশন যোগ করে।
- **Confetti**: কনফেটি ফেলে দেওয়ার ইফেক্ট, যা সেলিব্রেশন বা বিশেষ মুহূর্তকে আরও আনন্দময় করে তোলে।
- **Blur Fade**: উপাদানগুলোকে ব্লার করে দৃশ্যমানতা পরিবর্তন করার ইফেক্ট।
- **Text Reveal**: টেক্সটকে ধীরে ধীরে প্রকাশ করার জন্য একটি সুন্দর ইফেক্ট।
- **Parallax Scroll**: স্ক্রল করার সময় ব্যাকগ্রাউন্ডের উপাদানগুলোকে ডিফারেন্টিয়াল মোশনে সরানোর ইফেক্ট।
- **Ripple Button**: বাটনে ক্লিক করলে রিপল ইফেক্ট সৃষ্টি হয়।
- **Glitch Effect**: টেক্সট বা ইমেজে গ্লিচ (দৃশ্যমান বিকৃতি) ইফেক্ট যোগ করে।
- **Neon Glow**: উপাদানগুলোর চারপাশে নিয়ন গ্লো ইফেক্ট সৃষ্টি করে।
- **Hover Pop**: মাউসের হোভার করার সময় উপাদানগুলোকে পপ করার ইফেক্ট।
- **Wave Animation**: একটি তরঙ্গ ইফেক্ট যা বিভিন্ন উপাদানের উপর প্রয়োগ করা যেতে পারে।
- **Flip Card**: কার্ড উপাদানকে উল্টানো যায়, যেটি সামনের এবং পিছনের উভয় তথ্য প্রদর্শন করতে পারে।
- **Image Zoom**: ইমেজে জুম করার ইফেক্ট, যেটি মাউসের হোভার করার সময় সক্রিয় হয়।
- **Shadow Lift**: উপাদানগুলোর চারপাশে ছায়া যুক্ত করার মাধ্যমে তাদের উঁচু দেখানো।
- **Typing Text**: টাইপিং এনিমেশনের সাথে টেক্সট প্রদর্শন করা।
- **Lightbox Gallery**: ইমেজ গ্যালারির জন্য একটি লাইটবক্স ইফেক্ট।
- **Accordion Menu**: কন্টেন্টের জন্য একটি একর্ডিয়ন ইফেক্ট।
- **Tooltip Hover**: টুলটিপ প্রদর্শনের জন্য হোভার ইফেক্ট।
- **Rotating Carousel**: ঘূর্ণায়মান কারাউজেল, যা ইমেজ বা কন্টেন্ট প্রদর্শনের জন্য ব্যবহৃত হয়।
- **Particle Background**: ব্যাকগ্রাউন্ডে পার্টিকল এনিমেশন যুক্ত করে।

