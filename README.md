# Language Model in Shakespeare's style

Generating new texts in Shakespeare's style

## Using LSTM's to generate new writings

# Examples

```
seed == now the world's fresh ornament,
         and only herald 

 Machine written paragraph:
 now the world's fresh ornament,
  and only herald hangs on the ground and like a mercy by his wall
    can send thee in the friends of their wars, man in the wind;
    and when i do not come such best canterbury.
    this is my too capt a sword to the compality
    and not a traitor rest fall are article and
    care with point looks and speak and let a word in natural walks
    and be no man make him and dead as more
    that thou...

seed ==== क्क बेखबर भाे खाेजे सबै ती कुना
लुट्छाै मात्र कि द

 Machine written paragraph 
 क्क बेखबर भाे खाेजे सबै ती कुना
लुट्छाै मात्र कि देख कनेकाे मुन्छस्छ।
शाे भुन्छ जन्याे छ छन ।।
खुका होमा सदे बेखा मसमा।।

गाे काे काे जो पार।।
मातेर हो मान सुव जर्दै अन्।।

हाँ दान बोखा बने बधा सवै होश्छ।
पन्द्छ भाल अथिका छ लौम्यो न भनु ।

पारो केर मारा नागनै भनि तिर।।

हेर हुम्र जागाँ मसना दुश खिन्द नाव्याा।
हिन्दै बस्न भुन्छ न्याउँनै माग्र।।

सु सुन्दछ को दुख जन्दछ काे।
पार्दा तिरा ता काे सतै यहे ।।

माेको हुन् पार्छ साहा रोध हाे कधान।।
काि किर
```


## Playing around with temperature sampling to create diverse writing or confident writing for same seed

### When temperature is low, 0.1 i.e. diversity is low. This is words that the machine is very confident

```
seed ==== for she is the beauty of the skin that holds in my

 Machine written paragraph:
 for she is the beauty of the skin that holds in my son,
    and the state of the parts of the country,
    and the country that i say the country that i say the prince of such a service
    that we will be the country than the seal of the countrymen,
    and the country that i will not be a soul
    and the first and the country and the state
    that we shall be the state of the state of the state
    and the state of the country shall be so sou
```

### Same seed but with high temperature of 0.6

```
seed ==== now the world's fresh ornament,
  and only herald 

 Machine written paragraph 
 now the world's fresh ornament,
  and only herald hangs on the ground and like a mercy by his wall
    can send thee in the friends of their wars, man in the wind;
    and when i do not come such best canterbury.
    this is my too capt a sword to the compality
    and not a traitor rest fall are article and
    care with point looks and speak and let a word in natural walks
    and be no man make him and dead as more
    that thou oft and the mo
```

### Now with very high temperature of 2 i.e. high diversity

```
seed ==== for she is the beauty of the skin that holds in my

 Machine written paragraph 
 for she is the beauty of the skin that holds in my ho't cit whithfei!cbur
  h; likeferved mry? driy, hycks,sol.
  first citizen. it' cushiot yz'orail:
  well hu bass, caa i bags;
    oo, aler; a < wess; or tuquguys-
  oph. weoi'y hemy swa. kmy oxly,
     reus;. take myhpkilr.hingdon.
  orlando.egacmbefrude's. doltelogt] vellus
 
  iardinna. , bitionmera.

  cactori]-bidst?
  riched ho,[it with vac
    byu itquepir exepegitf
   oorsqu't grestgomje
```

### It is all jiberish in temperature = 2 where as shows very narrow vocab in temp = 0.1. Gives us good intuition of temperature sampling.
