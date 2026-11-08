# 길 위의 사도들 · The Apostles on the Way

**Live site / 웹사이트:** https://chanwoo777.github.io/apostles-timeline/

An interactive road map of the twelve apostles, Matthias and Paul, from the day Jesus called them, through the cross and the empty tomb, to the day each one died. It focuses on what they did after the resurrection, and weighs the historical witnesses for how each apostle died. In English and Korean.

열두 사도와 맛디아, 바울이 예수님께 부르심을 받은 날부터 십자가와 빈 무덤을 지나 각자 생을 마칠 때까지 걸어간 길을 지도와 연표로 따라가는 웹페이지입니다. 부활 이후의 사역을 중심으로, 사도들의 죽음에 관한 역사적 증언을 시기별로 저울질해 보여 줍니다. 한국어와 영어로 볼 수 있습니다.

## What it does / 기능

- **Pick an apostle** from the list of 14, grouped the way the Gospels list the Twelve.
- **Walk his road** one milestone at a time. A paved road means Scripture, a stone marker means an event recorded by historians, and a footpath means early church writers and tradition.
- **The map follows along.** Historical events elsewhere in the world, such as the fire of Rome (Tacitus) or the stoning of James the Lord's brother (Josephus), get their own marker.
- **Every source outside the Bible is named and dated,** with how many years after the event it was written and how close the writer stood to the apostles.
- **How did he die?** Each apostle has a case file: the verdict and its strength on a five-level scale, how, where and when he died, who sentenced him, every witness in date order, other accounts, his grave and relics, and historian Sean McDowell's rating.
- **All the apostles on one map:** drag a year slider from AD 30 to 100, or press play, to watch the apostles spread out from Jerusalem, travel, and die one by one, until only John is left at Ephesus.
- **Where the New Testament was written:** all 27 books with their likely date, place and author, and how we know the place (the book itself says, inferred from the book, church tradition, or unknown). Gold markers show each book appearing on the year map where it was written.
- **The deaths board** compares all 14 at a glance. **The witnesses** timeline places every source between AD 30 and 450.
- **한국어 / English** button switches the whole page. Korean uses the 개역개정 and links to the Korean Bible Society (대한성서공회). English uses the NIV and links to BibleGateway.
- **Light and dark mode,** and a layout that works on a phone.

## Sources and text / 출처

Milestones are retold in plain words with short quotations, and each one links to the full passage:

- English: New International Version (NIV) on [BibleGateway](https://www.biblegateway.com/versions/New-International-Version-NIV-Bible/). NIV © Biblica.
- 한국어: 개역개정 on [대한성서공회](https://www.bskorea.or.kr/bible/korbibReadpage.php?version=GAE&book=jhn&chap=1). 개역개정 © 대한성서공회. Korean quotations were checked word for word against the Korean Bible Society's text.

Historical witnesses are paraphrased, not quoted. They include Josephus, Tacitus and Suetonius; Clement of Rome, Ignatius, Polycarp and Papias; Dionysius of Corinth, Hegesippus, Irenaeus and Polycrates; Clement of Alexandria, Tertullian, Origen, Eusebius and Jerome; the apocryphal Acts and later legends; and archaeology such as the Gallio inscription, the Takht-i-Bahi inscription and the excavations under St Peter's and at Hierapolis. The modern assessment comes from Sean McDowell, *The Fate of the Apostles* (2015; 2nd edition 2025).

Only Scripture is the Bible. Everything else is marked as history or tradition. The timeline places the crucifixion in AD 30, and all dates are approximate. Dates and places for the New Testament books follow a common conservative reckoning; many scholars date some books later. Routes join known places; the Bible rarely names the roads the apostles took. Coastlines come from [Natural Earth](https://www.naturalearthdata.com/) (public domain).

## How it's built

Plain HTML, CSS and JavaScript with no build step and no dependencies. Fonts come from Google Fonts.

| File | Purpose |
| --- | --- |
| `index.html` | Page structure and the security policy |
| `styles.css` | Starlight design, light and dark mode, phone layout |
| `app.js` | Map, roads, witnesses, death files, translations and all the data |
| `favicon.svg` | Browser tab icon |
| `og.png` | Preview image shown when the link is shared (KakaoTalk, social media, messages) |

To try it locally, open `index.html` in a browser.

## Security

See [SECURITY.md](SECURITY.md).
