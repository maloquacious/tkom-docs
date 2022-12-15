---
sidebar_position: 11
---

# Individual Orders

INDIVIDUALS' ORDERS

Most Individuals will be hired from the Malkahai-operated Open Market for such, which works almost exactly like the Open
Market for Manuscripts, with Individuals going to the highest bidder and then teleported to the tribal Capital. Several
dozen different types of Individuals will be listed as available every turn, with between 1 and 8 of each type up for
grabs: a total of well over 100 different Individuals.

Each Type of Individual (eg. Master Farmers) will be listed as a separate "Lot No." for bidding purposes, and each tribe
may bid for 1 or more of those listed as available. Each tribe may also bid for as many different types of Individuals
as they wish, but this requires a separate order for each different Type, just like for Manuscripts. There is of course
a Minimu Bid for each Type, and this will increase most turns based on previous prices paid for that Type.

---

## BID FOR INDIVIDUAL

```text
BI (Lot #) (# Required) (Crowns)
```

    Example: BI 13 2 5000

To bid 5,000 Crowns each for two Individuals listed as Lot #13.

Following the order Code as usual, enter in the 2nd parameter the Lot No. of the required Individual Type, which may be
found on the Malkahai Open Market Listing shown in the previous turn's results. In the 3rd parameter enter the number of
this type of Individual you are bidding for (minimum of 1; maximum as available), and in the 4th parameter enter the
amount in Crowns that you are offering for EACH of the Individuals required.

The amount of the bid is important for three reasons. Firstly, future Minimum Bids for each Individual will be dictated
by offers made on previous turns; secondly, 10% of your bid is what you will pay the Individual in wages EVERY TURN in
future while in your employ, at least. Thus a bid of 2,500 Crowns for a Master Farmer on turn 1 might guarantee you
one (Min. Bid only 1,000), but it means you have to pay him at least 250 Crowns every turn thereafter. And last but not
least, whenever you hire a new Individual, all Individuals of the SAME type already in your employ will automatically
have their own wages increased to match the new Individual's wage, if theirs is currently lower than his: this is simply
because they would only complain anyway, so this saves you from having to issue orders to raise their wages to the same
level on the following turn.

It is important to note that bidding takes place at the very beginning of the turn, even before Manuscripts bidding.
This means that you can only spend Crowns which are in the Treasury at the end of the previous turn, not cash
transferred from other tribes or earned from the sale of commodities, etc.

However, you may bid for far more Individuals than you have cash for (providing you're selling enough commodities to
cover Maintenance & other orders), as bids will simply be ignored once you've run out of money. This is useful because
it means that you don't need to stake all your hopes on one or two bids: in the event that you're outbid on these, you
still then have the chance of other bids being successful instead. Dnote that you will be informed which bids succeeded
and which you were outbid on, but you will not receive any results for those bids which you could no longer afford to
make due to other, successful bids.

Bids are processed in the order of most to least value. Where two or more bids for the last remaining Individual of a
certain type are exactly the same, the successful bid is chosen randomly (NOT in Tribal order): for this reason, ALWAYS
throw an extra Crown or two into the bid to reduce the risk of identical bids, eg. 2503 not 2500.

---

## TRANSFER INDIVIDUAL

```text
TI (Indiv #) (To Type #1-4) (To ID #)
```

Types are: 1 = Army 2 = Town/City 3 = Fort/Gem Mine/Tower 4 = Shrine

    Example: TI 43 1 13

To transfer Individual #43 to Army #13.

The vast majority of Individuals do their work without the need for any specific orders to do so: all you need to do is
move them about as required. Where an Individual requires input from you to perform a specific order not mentioned here,
this will be detailed on the applicable Supplementary Rules Sheet. The above order to move an Individual between two
different controlled settlements or Armies is really all that most Individuals will ever require.

For the Transfer Individual order the destination location may be up to FOUR hexes away from the starting location, but
each Individual may be issued only a single Transfer order per turn. The ONLY Individuals who cannot be given this order
are the very special Andaluziak Rangers.

An Individual cannot be transferred into or out of a settlement which is under siege. If located with an Army any
Individual will automatically follow the army's regiments if the entire army is transferred into a different army or
settlement, so this TI order needs to be used only when an Individual is to be sent away from his current companions.

---

## TRANSFER INDIVIDUAL

```text
DI (ID #) (ID #) (ID #)
```

    Example: DI 3 7 19

To dismiss Individuals #3, #7 and #19 from your employment.

Occasionally you might wish to sack a particular Individual, such as when you're going bankrupt or more likely, when
you've reached the limit of 50 and want to get rid of some lesser Individuals to make room for better-skilled ones.

With the above order you may dismiss up to three specified Individuals per order used, but note that you will still have
to pay them their final wages that turn (no orders may given to them, however).

---

## CHANGE WAGES

```text
CW (Indiv #) (Amount) [Gem Type 1-7]
```

Please note: Gem Type required only if Individual is an Andaluziak Ranger.

    Example A: CW 9 5000

To increase the wages of Individual #9 to 5,000 Crowns per turn.

    Example B: CW 17 100 1

To increase the Gemstone wages of Individual #17 (who must be an Andaluziak) to 100 Pearls (Gem Type #1) per turn.

From time to time you will hear Individuals complaining about their current wages, in fact this could happen quite a lot
if you have a tendency to be tight-fisted! Individuals of all types are aware of what their comrades are being offered
on the Open Market every turn, and it is against this ever-increasing amount (10% of it, anyway) that they will value
themselves.

Thus once Master Farmers are being hired for considerably more than you are paying your own, your Master Farmers will
demand higher wages and threaten to depart your services and go back onto the Open Market. The above order is provided
to enable you to increase the wages of complaining Individuals whose services you would prefer not to lose.

Simply enter the complaining Individual's ID No. in the second parameter, and then his new wage (actual amount) in the
third. If this is not sufficient he will depart without further word. Note that this order should in future also be sued
for Andaluziak Rangers (and Amount in the 3rd parameter is therefore in Gems, not Crowns, and Gem Type 1-7 is entered in
the 4th parameter).

Note that you cannot change the "wages" for the Warlord, Champions, High Priests or Great Heroes, nor may you actually "
Dismiss" these Individual types. Each will have an ever-increasing cost which you must budget for every turn,
regardless.

---

## GLOBAL WAGES

```text
GW (% increase) [Type ID#] [Type ID#]
```

    Example A: GW 30

To give a 30% increase in wages to ALL Individuals in your employ.

    Example B: GW 50 36 85

To give a 50% increase in wages to all Individuals of Type #36 and #85.

Let's face it, sometimes you might just witness a veritable wage riot, with numerous greedy Individuals all clamouring
for wage rises on the same turn.

Rather than use an entire Order Sheet keeping everyboyd happy, the above order will be handy for those times when the
more specific CW order does not suffice.

The Global Wages order allows you to give some or all of your hired Individuals a percentage increase, by entering this
figure in the second parameter:
eg. putting 50 in the 2nd parameter will increase a 1,000 wage to 1,500 and a 2,000 wage to 3,000 etc.

Leaving the remainder of the order entirely blank will have the effect of giving ALL hired Individuals this percentage
wage increase, but as such generosity will only rarely be necessary you also have the option to limit the increase to
just one or two different TYPES of Individuals, eg. just all the Master Farmers and/or Plains Trackers, or any other
combination desired. This is achieved using the otherwise-blank 3rd and 4th parameters as shown above, by simply
entering the Individual's TYPE#. A Type# for any Individual may be determined by simply deducting 500 from its
Supplementary Sheet#, thus Plains Trackers (Sheet #554) are Type 54, and Master Weavers (Sheet #603) are Individual Type
103, etc.

You may enter none, one OR two specific Individual Types per GW order.

Incidentally, the Individual Type Numbers are also used by the Malkahai as LOT Numbers on the Open Market, should you
find this somewhat easier on the brain than having to subtract 500 from the Sheet # (chuckle).

---

## NAME WARLORD

```text
NW New Name
```

    Example: NW Sir Wimpalot

To rename your tribal Warlord 'Sir Wimpalot' for some absurd reason.

If you wish you may personalise your own character with a new name of no more than 25 characters in length, including
spaces. Simply enter NW as the order Code and enter the new name in the 4th parameter. Please keep the names within the
scenario.

---

## TRAIN CHAMPION

```text
TC (Weapon Ind. ID#) (Champ ID#) (Skill 1-5)
```

    Example: TC 14 26 1

To instruct Individual #14 (who must be a Weapons Trainer, Weapons Instructor or Weapons Master) to train Individual
#26 (who must be a tribal Champion) in Whirlwind Attack Skill.

Skill Tactics are:

|Code|Meaning|
|---:|-------|
|1|Whirlwind Attack Skill|
|2|Strong Attack Skill|
|3|Feint Attack Skill|
|4|Cautious Attack Skill|
|5|Passive Attack Skill|

With the above order you may instruct a Weapons Trainer, Weapons Instructor or Weapons Master to train your Champion
specifically in a single Tactic Skill, if located in the same Town or City. This will boost the required Skill by around
3, 6 or 9% respectively, rather than these points being allocated randomly. This is useful to either strengthen a weak
point or improve a good one even more. Training takes effect after that turn's League bout. See also page . and
Supplementary Rules Sheet #502.

---

## CHALLENGE BOUT

```text
CB (Champ ID#) (Enemy's Rank#)
```

It is possible for Champions to issue a challenge against a specific other Champion every month (though only one other)
rather than leave it to the League judges to decide who he will next fight. To do so he must 'qualify' by either being
within three Rank places of the other Champion, or by having a difference of no more than 10 Rank Points regardless of
how many actual Ranks apart they might be. Thus on Turn 1 player Champions vary in Rank from 9 to 50 but all have
equal (zero) actual Rank Points so may challenge any of the other 41. Later on, however, the growing differences in both
Rank and Rank Points will prevent poor fighters from qualifying to challenge the best, and vice versa.

If more than a single Champion challenges the same one, the highest-ranking Challenger (ie. the one with the most honour
and prestige) will prevail. This also means that although you might challenge another, if someone else of even higher
rank challenged YOU on the same turn then your own challenge will be ignored and you will have to fight your challenger
rather than the Champion you had hoped to challenge yourself. This would indeed be unfortunate, because to throw down
the gauntlet to the Champion of a specific enemy it will cost a total of 300 Crowns x Turn No. on which the challenge is
made, regardless of whether it is actually successful or not. Note that a legitimate challenge cannot be refused
however, only displaced by a higher-ranked Champion issuing a challenge to either yourself or your intended target,
which will supersede your own challenge.

Soundly defeating the Champion of a current or intended neighbouring enemy tribe is of course a very effective means of
weakening their entire tribal morale, while bolstering your own. There are no League rules preventing Champions from
issuing repetitive challenges against the same enemy Champion every single month, indeed it even seems to be quietly
encouraged. It is important to note that this fight would not take place until the Turn after the Challenge is issued (
you still have to fight your current bout), which means that after this fight the challenge may no longer be legal and
would be refused, but you would still have to pay for the challenge ritual itself.

---

## RECRUIT ANDALUZIAK

```text
RA (Hiring ID#) (Gem Type#) (Gem Amount)
```

Gem Types are:

|Code|Meaning|
|---:|-------|
|1|Pearl|
|2|Jade|
|3|Emerald|
|4|Sapphire|
|5|Ruby|
|6|Amber|
|7|Diamond|

    Example: RA 297 3 5

To offer Andaluziak #297 - 5 Emeralds in wages, immediately and for every future turn, should he agree to work for you.

The Andaluziak Rangers of the land are a rare and strange breed of immortal shape-shifters, with fantastic powers. They
are attracted to stockpiles of the precious Gemstones, and occasionally will offer their varied, powerful services to
the Warlord of a tribe which has accumulated such stockpiles.

Should an Andaluziak offer you his services you will receive a Supplementary Rules Sheet on the subject, and beneath the
Individuals listing on your Turn Results you will be given his name and a 'Hiring ID#'. Should you wish to try to hire
the Andaluziak, enter the RA order on your Order Sheet and the Hiring ID# in the second parameter. In the third
parameter enter a Gem Type number 1-7, which obviously should be of a type for which you have stocks. Finally, in the
fourth parameter enter the number of actual Gemstones you're prepared to pay this Andaluziak both immediately and for
every future turn in your employ. Note that early in the campaign most Andaluziaks would be quite happy with just one or
two Gemstones, but later on they can become extremely expensive as demand for their potent services increases.

Should the Andaluziak not be prepared to accept your first offer, he would normally give you one further opportunity to
make a more reasonable offer, on the following turn, using this RA order again. Note that even if you successfully
recruit an Andaluziak, he may demand higher wages at a later date. To increase the wages of an Andaluziak in your
employ, you should use Order #32, Change Wages (CW).

Controlling two Andaluziaks permits you access to a greater range of powerful orders, and controlling three Andaluziaks
adds six more available orders, all of which are extremely powerful and fairly unique.
