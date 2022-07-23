## The Wynnic Olympics, 2022 Edition
##### Secret Event Writeup by bikesuper/FlamingoBike#6228

---

The secret event, also known as `??? 2`, started on the 5th of July and ended on the 23rd of July. Our team (Team Troms) has managed to complete it 2 days before the deadline, on the 21st.
The name references a quest in Wynncraft, called `???`, which gives the player no clear instructions on how to solve it, but instead gives out clues in an ARG style, and it was introduced as a puzzle for the community to figure out.

Alright, introductions aside, let's get started!

---

## Stage 0 - Event Hype!

The event started with the host, WithTheFish, telling everyone to head to a newly created channel, #information, which contained an image: ![https://cdn.discordapp.com/attachments/859834512002252830/995755656684511323/post-this-cat.png](https://cdn.discordapp.com/attachments/859834512002252830/995755656684511323/post-this-cat.png)
At this time, we were all very hyped, and having some experience with the 2020 edition secret event, the first thing we did was completely ignore that image and look around the channels of the discord.
We found some codes:
```
5FZKAEONMCDUCNXPPSD - at the top of #major-announcements
6WBYYSGDJZKUSKFRJMI - at the top of #scavenger-hunt-images
7UEXADHOVUXYAIMEMZG - in the channel description of #discord-server-rules
8RUSVKSELSYWALULEPA - pinned message in #general
```
We figured that the number at the beginning of the code was meant to impart some sort of order, and this meant that we needed to find at least 4 more (1-4), so we started searching elsewhere.
The Olympics has a forum post, and that is where we looked next.
We found some other codes:
```
9IDFLNJLRUIYIIIELER  - in the forum post's tags
10XHJITPJRVSQSDUNFXD - in one of fish's replies, on the first page
11HWOSAQTCWUEOXJDVND - in the calendar spoiler, at Monday, July 4th
12TCKTBBFQQCEVALUSVV - at the bottom of the post
```

We didn't know what to do with these codes yet, but we surely didn't miss the occasion to fantasize about which strange and obscure cipher Fish could have used this time (spoiler alert: there was no cipher involved).

---

## Stage 1 - Post this Cat

Not finding the first 4 codes, we were at a loss and decided to call it a day.
The day after, I wake up one of my team members who had noticed the name of the image posted in #information, which was called "post this cat".
I immediately recognized that phrase, and posted the first gifs found with the discord command `/tenor post this cat`, and surely enough we were done with stage 1!

---

## Stage 2 and 3 - Riddles!

Having solved stage 1, Fish gave us two riddles to work on, which were going to be stages 2 & 3.

Here is the first riddle:

```
I can be anyone at anytime, and if I want to I can say I am everyone.
You’ve met me more than once, and maybe you never knew it.
I have leapt from earth to the moon and am two hundred years old.
Despite this, my only power here comes from my words. 
Who am I?
```
The answer to this one was "A Liar".

Here's an explaination:

```
A liar could tell you that they are a certain person, even though they aren't.
Liars are common, and you maybe never figured out they lied.
The third line contains two lies.
Lying is done through words (either written or spoken).
```

Solving this riddle gave us access to the following information:
```
1 - 6;15;1;4;20;11;23;14;18;10;3;2;21;18;20;21;18;22
2 - 16;16;18;10;2;9;18;12;15;11;22;12;22;10;17;22;6;14
3 - 25;12;5;13;16;22;23;24;17;14;4;5;11;5;17;23;25;25
4 - 20;25;24;12;18;22;23;14;1;18;19;21;12;25;19;1;21;1
```

And we immediately recognized the format of the codes. We just had to use `A1Z26` to convert the numbers to letters.
At this point we had all the codes, even though we thought there might have been more.

```
1FOADTKWNRJCBURTURV
2PPRJBIRLOKVLVJQVFN
3YLEMPVWXQNDEKEQWYY
4TYXLRVWNARSULYSAUA
5FZKAEONMCDUCNXPPSD
6WBYYSGDJZKUSKFRJMI
7UEXADHOVUXYAIMEMZG
8RUSVKSELSYWALULEPA
9IDFLNJLRUIYIIIELER
10XHJITPJRVSQSDUNFXD
11HWOSAQTCWUEOXJDVND
12TCKTBBFQQCEVALUSVV
```

Here is the second riddle:

```
Many say I ride on horseback, alongside war. 
Yet people made art about me, in which I was longing for more.
Those who witness me may whine.
In a familiar place, my flesh appears to be twine.
What am I?
```
The answer to this one was "A Rat".

Here's an explaination:
```
Rats are associated with Pestilence, and Famine, which are some of the horsemen of the apocalypse, that "ride alongside war".
In the movie (art) "Ratatouille", Remy (a rat) longs to be a cook.
Most people would whine if they saw a rat.
In the familiar place Wynncraft, the rat tail item is represented with string.
```

Solving this riddle gave us access to this image: ![https://cdn.discordapp.com/attachments/992545070291091456/994845191519354940/2022-07-05_12.57.32.png](https://cdn.discordapp.com/attachments/992545070291091456/994845191519354940/2022-07-05_12.57.32.png)

And fish gave us the following prompt:
```
To access the next part of this grand challenge, you must state which 10 blocks you will replace this bedrock with.
- Ignore the snowy background it's literally just the first singleplayer world I had open
- To prevent brute-forcing, you can only state your answer 1 time per hour. I promise there is a legitimate way to figure out which blocks to place.
- You have to guess all 10 at once
```

---

## Stage 4 - Preparation to solve Stage 5

This stage is supposed to be a gateway to Stage 5, or the stage of the bedrock blocks.
We have to find something that will lead us to the blocks that we are going to guess, and it has to be something specific, since we are limited to one guess every two hours.

At this point, we started looking more at the codes, since they *could* have just been completed thanks to solving the riddle.
We started thinking more about word searches, or arranging the letters in a big grid and finding words inside it (this idea seemed very promising, especially because each code had the same amount of letters in it, after removing the number at the start).

We tried to use some word search algorithms online, and the only promising words we found were "Asher", and "Coins":

![https://cdn.discordapp.com/attachments/992545027773440090/995304452078710784/unknown.png](https://cdn.discordapp.com/attachments/992545027773440090/995304452078710784/unknown.png)

After looking at it more, we noticed that Asher is actually the name of an NPC in Wynncraft.
We got stuck here for a bit, but the following morning I noticed something.
Starting from the first row, second letter, "O", you can go diagonally down and find the word (or, name) "Ormrod", which i recognized to be the name of another NPC in Wynncraft.

After this discovery, I thought that we had to find the names of 10 NPCs, which would have somehow corresponded to 10 blocks.
I quickly wrote a script to search words in the big block, and created a dataset with NPC names from the Wynncraft wiki, leaving out those who had composite names (like "General Graken"), but still keeping them in the back of my head (I could very well just add "Graken" as a possible name).

Surely enough, the program found 9 out of 10 names in the big block!
I then started adding all the composite names, and it finally recovered the last name, "Cevalus" (from "Farmer Cevalus").

```
--- Trying Regular Names ---
Found Adigard in col VNYADIGARDDV
Found Asher in diag that starts at row 2 and col 1
Found Burtur in row FOADTKWNRJCBURTURV
Found Irlok in row PPRJBIRLOKVLVJQVFN
Found Legolus in diag that starts at row 1 and col 1
Found Leucsaa in col BLEUCSAAISOV
Found Ormrod in diag that starts at row 1 and col 2
Found Relend in col TQQSPRELENDU
Found Yavlis in col DJMLAYAVLIST
--- Trying Composite Names ---
Found Cevalus in row TCKTBBFQQCEVALUSVV
```

Here is the script, made with JavaScript and ran with Node (yes, I was too lazy to make a separate data file for the names).

```js
const names = ["Achper","Adigard","Agent","Ahmas","Aledar","Alem","Alice","Aluxander","Amadel","Amerigo","Amira","Anast","Ankou","Ansei","Ardulf","Argus","Ario","Ariodo","Arnod","Arwes","Aryn","Arzul","Asher","Aster","Atisun","Ava","Axelus","Bandit","Banker","Barden","Barman","Batelu","Bricot","Brie","Buendo","Bugabo","Bulbo","Burtur","Bylvis","Caissop","Calamaro","Calo","Caras","Celuuse","Ceyquin","Charlie","Chilye","Cidre","Cikal","Cinfras","Citizen","Comor","Corak","Czytash","Dado","Dalben","Damien","Damiral","Darnes","Dawm","Daxe","Death","Dejol","Dereg","Diro","Doan","Dobile","Dodegar","Dohstaj","Dolem","Dorroc","Doubiss","Drale","Drucksh","Dullahan","Dumble","Dure","Duvale","Dwendle","Edula","Efena","Elio","Elphaba","Elrund","Eluzterp","Enkser","Enzan","Eppo","Erisk","Erlard","Farcor","Favian","Felim","Ferndor","Flendar","Flodur","Forve","Frank","Fredris","Gaclux","Gale","Gana","Garas","Gardener","Garoth","Garull","Garvan","Gawrick","Geo","Gernald","Govid","Gracen","Grandon","Gregor","Grenot","Guard","Gurix","Haily","Hallfred","Hans","Harker","Hashr","Hazel","Heliorion","Hermit","Hilan","Homeless","Honip","Honynn","Hrona","Ibele","Identifier","Ildan","Irahe","Irlok","Irt","Isfurus","Jack","Jankan","Jared","Javen","Javier","Jaybip","Jenprest","Jill","Jitak","Jorkin","Juggler","Junes","Kaetan","Kale","Kansard","Kantor","Kaosuw","Karkun","Kelight","Kofis","Korun","Korzim","Kracken","Krattson","Kristoff","Kroac","Kroken","Laen","Laloire","Lanu","Lari","Leacen","Legolus","Lekal","Leucsaa","Lexas","Likeru","Lodog","Lozeg","Lucio","Lumilda","Malo","Marden","Margaret","Marston","Martim","Maxie","Mehme","Merloni","Miti","Monte","Mylo","Nakoba","Narder","Nedlom","Nettik","Nick","Nohno","Norsten","Nybun","Nyris","Obsessor","Olivin","Ollie","Omango","Ope","Orikal","Orja","Ormrod","Orphion","Otenu","Phief","Phinas","Piere","Plario","Pottur","Prentiss","Psern","Psilo","Ragon","Ranol","Rayshyroth","Reddy","Referick","Regulux","Relend","Rensa","Reshad","Rickeo","Rileen","Rinire","Rismor","Rohem","Rontaid","Rynb","Rynend","Rynver","Salesman","Sanba","Santa","Sayleros","Sayrr","Seasum","Seluc","Server","Sesad","Sherk","Siwel","Slykaar","Soldier","Soway","Squiddles","Squidward","Svin","Syni","Sytis","Takan","Talos","Tarek","Tarod","Tasim","Telvu","Tesha","Tharroli","Therck","Thomas","Tiek","Timmy","Tirt","Todd","Togak","Tolem","Tom","Torold","Troll","Trunan","Twendle","Tyko","Una","Valimare","Veekhat","Vesdar","Viola","Viraex","Voer","Volmor","Wedyf","Wirt","Worid","Worthington","Yahya","Yansur","Yavlis","Yobon","Yodbon","Yot","Yuge","Zenam","Zhight"];
const compositeNames = ["Antikythera", "Avoschief", "Bigbutch", "Dren", "Wavebreaker", "Ackbar", "Enduyn", "Fenor", "Kymer", "Lorias", "Olof", "Gert", "Hamsey", "Dranfor", "Gailard", "Hart", "Jackson", "Legendary", "Picard", "Urelix", "Berusia", "Prometheus", "Eric", "Uci", "Lykron", "Placardus", "Vade", "Cevalus", "Edwin", "Graken", "Lecade", "Gerald", "Lobo", "Snaga", "Klerodor", "Mayor", "Thief", "Burtan", "Gren", "Mael", "Nasea", "Eoric", "Linton", "Caritat", "Nami", "Martyn", "Siwel", "Nitram", "Cob", "Tylas", "Qira", "Carlos", "Caid", "Sasha", "Ynnos", "Reynauld", "Miyagi", "Klafson", "Inrekei", "Theorick", "Thomas"]

const grid = [
    "FOADTKWNRJCBURTURV",
    "PPRJBIRLOKVLVJQVFN",
    "YLEMPVWXQNDEKEQWYY",
    "TYXLRVWNARSULYSAUA",
    "FZKAEONMCDUCNXPPSD",
    "WBYYSGDJZKUSKFRJMI",
    "UEXADHOVUXYAIMEMZG",
    "RUSVKSELSYWALULEPA",
    "IDFLNJLRUIYIIIELER",
    "XHJITPJRVSQSDUNFXD",
    "HWOSAQTCWUEOXJDVND",
    "TCKTBBFQQCEVALUSVV"
]

let success = false;

console.log("--- Trying Regular Names ---");
tryFind(names);
console.log("--- Trying Composite Names ---");
tryFind(compositeNames);

function tryFind(names) {
    for (let name of names) {
        success = false;
        tryRow(name);
        if (success) {
            continue;
        }
        tryCol(name);
        if (success) {
            continue;
        }
        tryDiag(name);
    }
}

function tryRow(name) {
    for (let row of grid) {
        if (row.includes(name.toUpperCase())) {
            console.log(`Found ${name} in row ${row}`);
            success = true;
        }
    }
}

function tryCol(name) {
    for (let j = 0; j < grid[0].length; j++) {
        let col = "";
        col = grid.map(row => row[j]).reduce((prev, curr) => prev + curr, col);
        if (col.includes(name.toUpperCase())) {
            console.log(`Found ${name} in col ${col}`);
            success = true;
        }
    }
}

function tryDiag(name) {
    for (let i = 0; i < grid.length; i++) {
        if (success) {
            break;
        }
        for (let j = 0; j < grid[0].length; j++) {
            let diag = "";
            let stop = false;
            let k = 0;
            while (!stop) {
                if (i + k >= grid.length || j + k >= grid[0].length) {
                    stop = true;
                    break;
                }
                diag += grid[i + k][j + k];
                k++;
            }
            if (diag.includes(name.toUpperCase())) {
                console.log(`Found ${name} in diag that starts at row ${i + 1} and col ${j + 1}`);
                success = true;
            }
        }
    }
}
```

---

## Stage 5 - The Blocks

The first thing we thought, was to locate the NPCs and see which block they are standing on.
Later on, we will find that there was actually a clue to this in the image in #information ("[...] of a certain minecraft server where the immortals stand").

We get these blocks:

```
Leucsaa - Mossy Stone Brick
Asher - Coarse Dirt
Ormrod - Dirt
Adigard - Snow
Farmer Cevalus - Coarse Dirt
Yavlis - Double Stone Slab
Relend - Spruce Planks
Burtur - Spruce Planks
Legolus - Podzol
Irlok - Blue Wool
```

So we guess:

```
the blocks we want to replace the bedrock with are the following:
Mossy Stone Brick, Coarse Dirt [x2], Dirt, Snow, Double Stone Slab, Spruce Planks [x2], Podzol, Blue Wool
```

And it was correct!

---

## Stage 6 - The Triangle

For stage 6 we are given this prompt:

```
Congratulations! You’ve gotten past the first five stages. To progress to the meteors, you have another task ahead:
You must input 3 codes consisting exclusively of numbers. No cooldowns here as there are an unimaginable amount of combinations. You do get a clue though:
```

![https://cdn.discordapp.com/attachments/992545070291091456/995895826293477507/IMG_0666.jpg](https://cdn.discordapp.com/attachments/992545070291091456/995895826293477507/IMG_0666.jpg)

This stage had us stumped for quite a few days, as we didn't really how to extract three numbers with this information, although we had an idea: we could overlap this triangle on the Wynncraft map, and find three important locations that work well with it.

Fish had already given out some hints for this part:

```
- It's not a right triangle.
- There are no decimal points in the answer.
- Your answers don't need to be in a certain order.
- I'll only respond if it's correct
```

Since we couldn't find meaning in any of the promising overlaps of the triangle onto the map, I decided to do brute force calculation of the distances between cities, and various other points of interest.
So, I made the following script:

```js
const fs = require("fs");

const cities = {
    //"Legendary Island": [-1115, -2425],
    //"Nether Portal": [170, -1300],
    "Ragni": [-821, -1580],
    "Elkurn": [10, -1180],
    "Nivla Village": [-260, -1390],
    "Detlas": [470, -1582],
    "Maltic": [-562, -1927],
    "Ternaves": [825, -1606],
    "Nemract": [100, -2200],
    "Selchar": [100, -3150],
    "Almuj": [855, -1963],
    "Bremminglar": [700, -2100],
    "Llevigar": [-2024, -4395],
    "Rymek": [1310, -1350],
    "Bucie": [-1620, -4960],
    "Nesaak": [105, -800],
    "Lusuco": [-195, -340],
    "Iboju Village": [-750, -690],
    "Olux": [-1732, -5528],
    "Troms": [-840, -920],
    "Gelibord": [-1020, -5310],
    "Pirate Cove": [-700, -3100],
    "Efilim": [-1057, -5007],
    "Lexdale": [-615, -5435],
    "Aldorei Town": [-350, -4580],
    "Cinfras": [-445, -4939],
    "Thanos": [130, -5240],
    "Corkus City": [-1615, -2924],
    "Eltom": [930, -5500],
    "Relos": [-1700, -2300],
    "Thesead": [854, -5123],
    "Maex": [1460, -5278],
    "Rodoroc": [1211, -5190],
    "Kandon-Beda": [750, -4440],
    "Ahmsord": [1050, -4600],
    "Lutho": [981, -704]
};

const portals = {
    "Nether Portal": [170, -1300],
    "Light Portal": [-1052, -4290],
    "Dark Portal": [1320, -417]
}

const meteorStuff = {
    "BTp": [-807, -4340],
    "BSpawn": [2228, -6571],
    "BPlate": [2228, -6577],
    "YTp": [-1445, -5634],
    "YSpawn": [2493, -5751],
    "YPlate": [2490, -5751],
    "RTp": [119, -5704],
    "RSpawn": [2431, -6405],
    "RPlate": [2431, -6409]
}

const labNStuff = {
    "Mushroom": [-305, -7705],
    "Painting": [388, -3529],
    "Spoon": [-1472, -8447],
    "Mansion": [-1191, -5192]
}

const sussyStuff = {
    "Lusuco": [-195, -340],
    "Lutho": [981, -704],
    "Llevigar": [-2024, -4395],
    "Nivla": [-400, -1610],
    "Yahya": [-277, -1681]
}

const funny = {
    numbers: [4583, 4471, 1239],
    distances: [100000, 100000, 100000],
    taxicabDistances: [100000, 100000, 100000],
    distanceLines: ["", "", ""],
    taxicabDistanceLines: ["", "", ""],
}

function distance(p1, p2) {
    return Math.sqrt(Math.pow(p1[0] - p2[0], 2) + Math.pow(p1[1] - p2[1], 2));
}

function taxicabDistance(p1, p2) {
    return Math.abs(p1[0] - p2[0]) + Math.abs(p1[1] - p2[1]);
}

function findClosestFunnyNumber(number) {
    let minDistNum = funny.numbers[0];
    let minDist = Math.abs(number - funny.numbers[0]);
    for (let i = 1; i < funny.numbers.length; i++) {
        let dist = Math.abs(number - funny.numbers[i]);
        if (dist < minDist) {
            minDist = dist;
            minDistNum = funny.numbers[i];
        }
    }
    return [minDistNum, minDist];
}

function getLongestKeyLength(dict) {
    let length = 0;
    for (let key in dict) {
        if (key.length > length) {
            length = key.length;
        }
    }
    return length;
}

function calculateDistances(distancesDict) {
    let output = "";
    
    for (let city1 in distancesDict) {
        for (let city2 in distancesDict) {
            if (city1 == city2) {
                continue;
            }
            let dist = distance(distancesDict[city1], distancesDict[city2]);
            let taxiDist = taxicabDistance(distancesDict[city1], distancesDict[city2]);
            let minDistArr = findClosestFunnyNumber(dist);
            let minDist = minDistArr[0];
            let minTaxiDistArr = findClosestFunnyNumber(taxiDist);
            let minTaxiDist = minTaxiDistArr[0];
            let line = `${city1} <=> ${city2}`;

            if (minDistArr[1] < funny.distances[funny.numbers.indexOf(minDist)]) {
                funny.distances[funny.numbers.indexOf(minDist)] = minDistArr[1];
                funny.distanceLines[funny.numbers.indexOf(minDist)] = line;
            }
            if (minTaxiDistArr[1] < funny.taxicabDistances[funny.numbers.indexOf(minTaxiDist)]) {
                funny.taxicabDistances[funny.numbers.indexOf(minTaxiDist)] = minTaxiDistArr[1];
                funny.taxicabDistanceLines[funny.numbers.indexOf(minTaxiDist)] = line;
            }

            output += `${line} ${" ".repeat(getLongestKeyLength(distancesDict) - city2.length)}: [${dist}]CLOSEST_TO[${minDist}] or [${taxiDist}]CLOSEST_TO[${minTaxiDist}]\n`;
        }
    }

    output += `
Min Distances:
for ${funny.numbers[0]} : ${funny.distanceLines[0]}
for ${funny.numbers[1]} : ${funny.distanceLines[1]}
for ${funny.numbers[2]} : ${funny.distanceLines[2]}

Min Taxicab Distances:
for ${funny.numbers[0]} : ${funny.taxicabDistanceLines[0]}
for ${funny.numbers[1]} : ${funny.taxicabDistanceLines[1]}
for ${funny.numbers[2]} : ${funny.taxicabDistanceLines[2]}`;

    fs.writeFileSync("output.txt", output);
}

function calculateManualPoints(p1, p2) {
    console.log(`p1 <=> p2 : ${distance(p1, p2)} or ${taxicabDistance(p1, p2)}`);
}

calculateDistances(sussyStuff);
```

This also contained a data structure that kept track of the distances that were closest to the three sides of the triangle.
There is one fatal flaw in this method, and that is it assumes the triangle is able to be rotated, and flipped.
Later on, we would in fact find that this was not a possibility, thanks to a hint that fish gave out:

```
The numbers have a meaning but aren't completely precise.
Still, they give a good idea as to what the shape and scale of the triangle represent.
```

We eventually figured out that the cities that fit the triangle best were Cinfras, Lusuco, and Lutho, but we still didn't know what to do with this information.

Eventually, Fish posted another hint, which was supposed to apply to every team, so it had various pieces of information, and we had to identify which one was for us:

![https://media.discordapp.net/attachments/993919636313747549/997938561942818836/unknown.png](https://media.discordapp.net/attachments/993919636313747549/997938561942818836/unknown.png)

We figured out that the "Breaking Bad" part of it related to our stage.
Fish also said that there was no need of knowing anything about either Breaking Bad or Ratatouille.

Finally, we figure out the solution. After looking up Breaking Bad on Wikipedia to find some information, I notice that they use some elements of the periodic table to replace the first two letters of "Breaking" and "Bad".
So, we guessed 6 (C, Carbon, for Cinfras), 71 (Lu, Lutetium, for Lusuco), and 71 again, but to no avail.

Eventually, we find that the solution was converting the entirety of each name to elements.

![https://cdn.discordapp.com/attachments/992545027773440090/998284062185766994/unknown.png](https://cdn.discordapp.com/attachments/992545027773440090/998284062185766994/unknown.png)

The numbers of the answer are 6498733, 71908, 71169227.

---

## Stages 7, 8, 9 - The Meteors!

After completing Stage 6, we get hit with a lot of information! The prompt now is:

```
To proceed to the final stage, you must find 3 items to throw in a (figurative) hopper. You can only guess which items once per 4 hours, so be absolutely certain you know what they are. 

You can learn which item is which by completing a meteor.
```

And here I will list the meteors in the order we solved them, with their respective answers.

### RED METEOR

```
ACROSS:
#2 - Swordfish Weapon Type
#3 - In Kander and Lutho
#4 - What the 1st answer does
#6 - Forum Host
#7 - Support Mage
#9 - Out of place word

DOWN:
#1 - Order of 2nd answer
#5 - EWFA
#8 - Candles are basically this
```

![https://cdn.discordapp.com/attachments/992545070291091456/998107669862817922/unknown.png](https://cdn.discordapp.com/attachments/992545070291091456/998107669862817922/unknown.png)

This was a pretty straight forward puzzle. Find the correct words, put them in the correct places, and take out the letters in the blue squares to form the name of an object.
However, being a Fish puzzle, it wasn't short of tricks.

The definitions we struggled the most on were #1, #4, and #9.
For the first two, Fish eventually gave out a hint:

```
For the crossword, "1st" and "2nd" refer to the first and second riddle answers
```

and for #9, we eventually noticed that the image in #information had changed.
Take a look at this, and see if you can find the word out of place:

![https://media.discordapp.net/attachments/863264387615293471/998057774640549888/Screen_Shot_2022-07-16_at_9.44.29_PM.png](https://media.discordapp.net/attachments/863264387615293471/998057774640549888/Screen_Shot_2022-07-16_at_9.44.29_PM.png)

If you can't find it, the last line changed from `Valiant players, the red herring wishes you luck!` to `Valiant players, the beast wishes you luck!` and, therefore, the word out of place here was `beast`.

Here is the crosswords, fully completed:

![https://i.imgur.com/Azwjq8f.png](https://i.imgur.com/Azwjq8f.png)

As you may read from the image, Fish had told us that there was a mistake in the crosswords, and he would have told us the correct answer once we completed it.

The answer for the Red Meteor was: `Apple`.

### YELLOW METEOR

```
REDNAMMOCNOITACOLSIHTRETSOPMIREWOT

"The first thing you find here is the answer"
```

This string is a bunch of nonsense, but reversing it makes it way clearer:

`TOWERIMPOSTERTHISLOCATIONCOMMANDER`

We can split this into various words: `TOWER`, `IMPOSTER`, `THIS LOCATION`, `COMMANDER`.
At this point, we are stumped and we don't know what to do.

A couple of hints eventually make it clearer, and we now know what to do:

```
Every word you find is supposed to be a synonym for something else. This includes "commander" which is supposed to be "general --> generally".
And [this location] can be counted as one word
```

```
Okay I lied, "Imposters" doesn't have a synonym either. To find the word you're supposed to change "Imposters" to, look at https://www.imdb.com/chart/top/ and see which movie might have the equivalent of among us imposters in it. Part of that movie's title (with an added s at the end) is the 2nd word in the yellow meteor sentence.
To make it a bit more clear, for the yellow meteor, you'll be forming a sentence that's [something that's a tower] [something you get from the hint above] [synonym for This Location] Generally [5th word, you can find this word once you know what the other 4 are]
```

These hints were a godsend, since this was probably one of the most confusing parts of the puzzle.

We didn't know what to replace `Tower` with, but we found the movie to be `The Thing`, which would become `The Things` after adding the s at the end, and we figured we could replace `This Location` with `Here`.

After another hint, I decided to search "The Things Here Generally" in the official Wynncraft discord, and well, I was met with a surprising result:

![https://media.discordapp.net/attachments/998285059654160395/999304345755590676/unknown.png](https://media.discordapp.net/attachments/998285059654160395/999304345755590676/unknown.png)

So we knew the 5th word was `Wynncraft`.
Going back to the prompt, it told us that the answer was "The first thing you find here", and the first item you obtain in Wynncraft (in the tutorial) is the item `Tosach`, which was the answer.

### BLUE METEOR

```
One was a mere rodent.
One stayed in the barn.
The other lay close by.
The fourth wondered who was out there.
Can you find the possession of their friend?
```

Oh god - another riddle.
This one was a wild ride - we figured out that the second line referred to a `Cow` and the third line referred to a `Chicken` (from "lay"), but we got stuck on what the rest of the riddle could mean.

The hints for this were pretty strong - Fish gave away the fact that each line referred to a different animal (including the last one, so "friend" there was figurative) - and that the first one was actually a `Hamster`.

Another hint told us to pay attention to the words "Fourth" and "Who" for the fourth animal, and especially "Who" brought us to the conclusion that it was an `Owl`, as that word is *kinda* like the sound it makes.

It was our favourite time once again, finding what to do with this information, and eventually finding the answer.
I tried looking at something the animals have in common, even going as far as looking at their scientific classification, and guessing things about Dinosaurs. This, however, wasn't the answer, and we were stuck on this part for another, long, day.

The following day, we received the final hint, one that would finally end our suffering:

![https://media.discordapp.net/attachments/998284842829631580/999721938773618749/Screen_Shot_2022-07-19_at_12.57.43_AM.png](https://media.discordapp.net/attachments/998284842829631580/999721938773618749/Screen_Shot_2022-07-19_at_12.57.43_AM.png)

This hint pointed at the Emojis tab of discord. Going to the "Nature" section, I noticed that all of our animals are very conveniently lined up vertically...

![https://i.imgur.com/TUAMpnz.png](https://i.imgur.com/TUAMpnz.png)

...and that the 5th and final animal, their "Friend", was a `Snail`.
A Snail is actually a mob in Wynncraft, called "Sky Snail", and they drop an item called `Sky Snail Shell`, which was the third and final answer.

(The word "Fourth" in the Owl's line was supposed to indicate that all of the animals were, in fact, lined up on the 4th vertical line in the Discord Nature Emojis tab.)

Having guessed `Apple`, `Tosach`, and `Sky Snail Shell`, we finally proceeded to the 10th and **final** stage of this event.

---

## Stage 10 - You know what to post

We are given our final prompt:

```
With the three items in the hopper, the path opens ahead. There's only one puzzle left for you to solve, one that will wrap things back around to the beginning... 
```

![https://cdn.discordapp.com/attachments/992545070291091456/999202178881302600/you-know-what-to-post.png](https://cdn.discordapp.com/attachments/992545070291091456/999202178881302600/you-know-what-to-post.png)

This time, Fish had failed to hide the image name, and we immediately read its name: "You know what to post".
Given the prompt, we immediately started posting the same gifs as in Stage 1, but to no avail.
We then "posted this troll", even reposting the same image of the prompt.

Eventually, we found that the answer was posting the coordinates of that location on Wynncraft (`Troll Tower, X: 1099 Z: -2869`) and we were greeted with a message of Congratulations from the Host himself, for having completed the Event, `??? 2`!

---

## Special Thanks

Special thanks to all the other members of Team Troms, most of which helped me during this journey (in the order that they appeared in the Discord list at the time of writing this):

```
- GithubCopilot
- Matheuzinhow
- Moshi
- d3keract
- PokemonGamer
- unicat42
- Toboro
- Albin
- chryssie
- Crystallized
- ThEpicFerret
- WitherWings
```

And, of course, thanks to WithTheFish for making this experience!
