# Основы

Прежде всего, вам следует **вступить в отделение**.</br>
На некоторых серверах это даже принудительно — одиночных игроков после предупреждения могут кикнуть.</br>
Игра становится значительно интереснее и эффективнее, когда вы играете в слаженном отделении.</br>
Если вам нужна помощь, просто **спросите игроков в своём отделении**, что делать.</br>
По возможности используйте _Mumble_ — он широко применяется в PR. Игра в PR:BF2 без микрофона не даёт полного опыта, поэтому его наличие — разумное вложение.</br>
Если никто не отвечает, попробуйте вступить в другой отряд или воспользоваться общим чатом.</br>
В сообществе PR много игроков, которые охотно помогают новичкам.

Предполагается, что у вас уже есть базовое понимание _Battlefield 2_, включая навигацию по внутриигровым меню, таким как таблица счёта, карта и выбор комплектов.</br>
Чтобы познакомиться с интерфейсом PR, вы можете запустить офлайн-матч, выбрав Co-operative или Multiplayer, затем Create Local, нажать Add Map и после этого Deploy.

## _Выбор снаряжения и появление на поле боя_ {#kit-selection-and-spawning}

* При начале игры рекомендуется появляться только с комплектом стрелка (rifleman) с выбранным прицелом. Это позволит лучше освоить базовые основы игрового процесса.
* Изучив основы пехоты, вы можете попросить своего КО назначить вам специализированный комплект, когда почувствуете готовность. Если вы хотите опробовать новое снаряжение или технику, лучше сделать это в режиме co-op, не мешая членам отряда и не рискуя командными ресурсами.
* Специализированные и более сложные в использовании комплекты, как правило, ограничены и могут быть получены только при выполнении определённых условий внутри отделения. Эти зарезервированные комплекты доступны в ограниченном количестве для всей команды, поэтому перед запросом всегда следует спрашивать разрешение.
* Комплекты можно запрашивать из главного меню возрождения \(по умолчанию: **Caps Lock**\), из ящика снабжения \([см. Logistics](the_basics.md#logistics)\) или с задней части БТР / БМП. Чтобы иметь возможность запрашивать комплект из ящика или техники, вы должны состоять в отделении.

В PR:BF2 нельзя появляться на каждой контрольной точке, находящейся под контролем вашей команды. Доступные точки возрождения:

* **Ралли-поинт вашего отряда (RP)** — зелёный круг вокруг точки возрождения с номером вашего отряда рядом. Время существования RP зависит от его расположения относительно FOB команды. Примечание: если вы попытаетесь появиться на RP другого отряда, вы автоматически появитесь на своём RP или на ближайшем FOB. Если таких точек нет, вы будете перемещены на главную базу команды. При захвате противником RP исчезает. RP доступны не для всех фракций. \([см. Deployable Structures](the_squad_leader.md#deployable-structures)\)

{% figure "../assets/rally.png" %}
  Rally point.
{% endfigure %}

* **Командные ралли-поинты, специфичные для карты**. Обычно они исчезают через 5 минут после начала раунда и могут использоваться всей командой. Максимум 12 человек могут появиться на таком RP до его исчезновения.
* **Ралли-поинт командира**. Может быть размещён только командиром при условии, что рядом с ним находятся командир отряда и 4 бойца. На карте обозначается ралли-поинтом с буквой «C».
* **Развёртываемые передовые операционные базы (FOB) или укрытия** могут использоваться всей командой для возрождения, но должны быть построены перед вводом в эксплуатацию. На карте отображаются как точка возрождения с зелёным треугольником. Становятся активными через 90 секунд после постройки. Точка становится недоступной для возрождения на 30 секунд, если 1 противник находится в радиусе 10 м, 2 — в радиусе 50 м, 4 — в радиусе 100 м или 8 — в радиусе 150 м. \([см. Deployable Structures](the_squad_leader.md#deployable-structures)\)
* В режиме Insurgency обороняющаяся команда повстанцев может появляться на **тайниках с оружием**, которые ещё не раскрыты противнику — это так называемые неизвестные тайники. Эта точка возрождения также блокируется, если враги подходят слишком близко, аналогично FOB.

{% figure "../assets/fob.png", "../assets/hideout.png", "../assets/cache-weapon.png" %}
FOB, Hideout & weapon cache.
{% endfigure %}

* **Штаб команды, главная база или постоянный FOB.** Это единственная точка возрождения, которая всегда доступна.

{% figure "../assets/acv.png" %}
Armored Command Vehicle (ACV), встречается только на главных базах.
{% endfigure %}

* На некоторых картах доступны **парашютные точки возрождения**, имитирующие воздушный десант. Они отображаются как движущиеся маркеры возрождения на мини-карте. Выберите один из них, и вы появитесь с автоматически раскрытым парашютом.

## _In-game interface (HUD)_ {#hud}

* В игровом интерфейсе PR:BF2 игроки получают **персональные сообщения**, которые видны только конкретному игроку. Они используются для информирования о различных игровых событиях, например:
  * причина, по которой запрашиваемый комплект не был выдан;
  * причина, по которой запрошенное развёртываемое укрепление не может быть построено;
  * уведомление о необходимости покинуть технику или текущее место в ней во избежание наказания.
* В PR также используются **HQ Notifications**, которые отображаются крупным оранжевым текстом в верхнем левом углу экрана. Эти уведомления информируют о текущих целях, ходе миссии и других важных сообщениях.
* Прямые сообщения от администраторов сервера и некоторые типы игровых уведомлений отображаются оранжевым текстом ближе к центру экрана. Часть из них носит информационный характер, тогда как другие, особенно сообщения администраторов, могут требовать вашего внимания.
* Если вы пропустили сообщение или объявление, например результат голосования за карту, вы можете просмотреть его снова, удерживая **Tab**, кликнув правой кнопкой мыши для активации курсора и затем выбрав вкладку **Notifications**.
* **Прицельные перекрестия** были удалены с экрана. Для точной стрельбы необходимо нажать клавишу альтернативного огня, чтобы прицелиться через прицельные приспособления оружия, либо использовать BUIS для ближнего боя (см. [главу об оружии](weapons_and_equipment.md#buis)).
* **Большинство 3D-иконок было удалено** для всех игроков. Крайне важно идентифицировать цели перед открытием огня, чтобы избежать дружественного огня. Изучение различий в камуфляже, флагах и силуэтах пехоты разных фракций помогает быстрее распознавать противника. Например, чтобы определить командира отряда, обратите внимание на радиоантенну, выступающую вверх из его рюкзака.
* **Индикатор здоровья отсутствует**, показывающий текущее состояние бойца. ([см. Health Management](the_basics.md#health-management))
* **Счётчик боеприпасов** отображает только режим огня оружия и количество оставшихся магазинов.
* Чтобы оценить **количество патронов, оставшихся в магазине**, можно открыть меню связи (удерживая **Q**) и посмотреть на визуальный индикатор боеприпасов.

{% figure "../assets/ammo_check.png" %}
Индикатор боеприпасов.
{% endfigure %}

* **Медик** может видеть, насколько завершено лечение бойца, по индикатору HUD прямо над компасом. Пехота аналогичным образом может наблюдать, сколько времени осталось до завершения строительства укрепления.

{% figure "../assets/heal_build_bar.png" %}
Индикатор лечения / строительства.
{% endfigure %}

* **Сообщения об убийствах отсутствуют** (за исключением дружественного огня). Даже таблица счёта не показывает, кто жив или мёртв в команде противника. Если вам необходимо узнать, погиб ли игрок, следует искать его тело.
* Только авиация и некоторые водители бронетехники используют постоянную **мини-карту** в HUD. Полная карта доступна всем игрокам.
* **Текущую карту и слой** можно увидеть в верхней части экрана при открытии карты с меню отряда / комплектов.
* Использование небольшой стрелки (слева от таймера) отображает **информационную панель ресурсов карты**, включающую все доступные на карте машины, таймеры возрождения дружественной техники, а также информацию о том, появляется ли техника с задержкой или возрождается после уничтожения. Вне-картовые миномёты или артиллерия, также известные как Area Attacks, обычно ограничены 3–4 применениями и могут использоваться только после достаточно длительного времени ожидания.

{% figure "../assets/assets.png" %}
Информационная панель ресурсов карты.
{% endfigure %}

* **Оставшиеся билеты** вашей команды и оставшееся время раунда можно увидеть только на экране отряда. Билеты команды противника не отображаются.
* **Подавление** возникает, когда вы находитесь под плотным огнём из стрелкового оружия, тяжёлых вооружений или рядом с взрывами. Экран размывается и начинает «дрожать». Этот эффект имитирует снижение способности вести эффективный ответный огонь под огнём противника.

{% figure "../assets/suppression.png" %}
Обычный вид игры (слева) и эффект подавления (справа).
{% endfigure %}

* В нижнем левом углу экрана расположена шкала выносливости. Бег и прыжки уменьшают запас выносливости, а её восстановление происходит при отсутствии этих действий. Когда выносливость снижается до 50 % или ниже (что обозначается миганием), бег становится невозможен, однако прыжки всё ещё доступны.
* Когда игрок находится в состоянии **dead** (обычно называемом dead-dead), его невозможно оживить, и вместо окружающего мира отображается чёрный экран с соответствующим сообщением.
* Точность оружия и отклонение пуль зависят от интенсивности движения. При прицеливании появляется **индикатор отклонения** над компасом, показывающий текущий уровень разброса. Чем шире индикатор, тем выше разброс; если две точки сходятся в одну, оружие достигло низкого отклонения, однако для достижения максимальной точности может потребоваться ещё один-два момента.
* **Автоматическая система отметки целей на карте** для пехоты была удалена. Авиация по-прежнему может отмечать цели из техники.
* Офицеры могут отправлять **contact-репорты** командиру или использовать радио для ручной установки маркеров на карте команды. Обычные солдаты могут лишь выкрикивать общее предупреждение при обнаружении противника.
* **Radio Commo-rose (по умолчанию: Q и T)** содержит элементы с двойной функцией. Левый клик по пункту **«RELOADING / CEASE FIRE»** сообщает окружающим, что вы меняете магазин, тогда как правый клик приказывает прекратить огонь. Тот же принцип применяется к пунктам **«GO, GO, GO / FALL BACK»** и другим подобным командам.

{% figure "../assets/commorose.png" %}
Commo-rose при нажатии Q.
{% endfigure %}

* Вы можете **ориентироваться на карте**, используя индикатор направления, расположенный вокруг иконки вашего персонажа.
* При использовании определённого оружия или оборудования основное **радио-меню связи** заменяется небольшим контекстно-зависимым меню. Например, удерживая бинт или медицинскую сумку, вы можете использовать команду **«FIRST AID»**, чтобы сообщить находящимся рядом игрокам, что вы готовы их лечить. Многие элементы снаряжения и некоторые виды оружия используют такие контекстные меню.

## _Health Management_ {#health-management}

Оружие в Project Reality обладает высокой летальностью, и рано или поздно вы получите ранение и начнёте истекать кровью. Несмотря на то что в HUD PR отсутствует индикатор здоровья, при снижении уровня здоровья ниже 75 % появляются визуальные предупреждения — периодическое затемнение экрана с эффектом туннельного зрения. При уровне здоровья ниже 25 % вы услышите кашель и тяжёлое дыхание, а при 10 HP вы полностью потеряете выносливость и не сможете восстановить её, пока не вылечитесь хотя бы выше этих 10 HP. Во время кровотечения эффект туннельного зрения и затемнение экрана будут усиливаться, всё сильнее снижая вашу боевую эффективность.

### Healing

После получения статуса кровотечения вы будете постепенно терять здоровье, пока в конечном итоге не потеряете сознание. Чтобы этого избежать, у вас есть два способа лечения. Почти каждый комплект экипировки включает **перевязочный пакет (field dressing)**, который выбирается соответствующей клавишей или прокруткой оружия. При нажатии кнопки огня он выбрасывается на землю. Через одну–две секунды перевязочный пакет исчезает, а игрок, находящийся рядом с ним, восстанавливает 25 % от максимального здоровья. Однако сам по себе перевязочный пакет **не останавливает кровотечение**. Если после его применения уровень здоровья всё ещё ниже 75 %, кровотечение продолжится, и вы лишь выиграете немного времени. В таком случае необходимо использовать дополнительные перевязочные пакеты (если они есть) либо, при необходимости, подбирать их с тел противников.

Подавляющему большинству комплектов выдаётся только один перевязочный пакет для экстренных ситуаций, поэтому игроки сильно зависят от медиков своего отряда или команды для полного восстановления здоровья. Роли **Medic** и **Collaborator** — единственные, кто получает аптечку первой помощи, позволяющую лечить союзников без использования перевязочных пакетов. При получении ранений используйте Mumble или меню связи (клавиша **Q**) и команду «Medic», чтобы привлечь внимание медика. Однако, в отличие от BF2, медик не может просто бросить аптечку на землю — он должен держать её в руках, находиться вплотную к раненому игроку и удерживать левую кнопку мыши, глядя на него. Звук рвущихся бинтов означает, что лечение началось. Полное восстановление занимает около 15 секунд, поэтому убедитесь, что вы находитесь в безопасном месте.

{% figure "../assets/fielddressing.png", "../assets/kit.png", "../assets/epipen.png" %}
Перевязочный пакет, аптечка первой помощи и эпипен.
{% endfigure %}

### Reviving

Если вас не успели вылечить вовремя, вы потеряете сознание, и на экране появится сообщение о критическом ранении. Это **не означает смерть**. В состоянии критического ранения медик может оживить вас в течение 5 минут, сохранив ценные билеты команды. Вы можете использовать Mumble для координации медика, сообщив своё местоположение через локальный канал (**H**) или **радиоканал отряда (NumPad 0)**. Также вы можете нажать **Call Medic**, чтобы временно отметить себя на карте всех медиков команды.

Для оживления медик выбирает **эпипен** в меню оружия (по умолчанию: **5**) и, держа его в руках, вводит инъекцию эпинефрина в центральную часть туловища бессознательного игрока, удерживая левую кнопку мыши. После этого игрок приходит в сознание, но имеет лишь около 10 % здоровья и всё ещё нуждается в лечении. Медику и только что оживлённому игроку следует найти безопасное место и продолжить процесс лечения там.

Если тело игрока находится на неровной поверхности или в неудобном для оживления положении, необходимо сначала перетащить его в более подходящее место. Чтобы перетащить тело, медик должен находиться в положении приседа и оставаться в нём. Затем следует выбрать слот оружия **drag** (по умолчанию: **2**) и начать перетаскивание. Перетаскивать тело можно в любом направлении, включая движение назад.

{{ "Video Tutorial - Reviving" | youtube("auBgiI8IxWE") }}

### Death

В некоторых случаях игрок не может быть оживлён, например если он был убит внутри техники. Также если игрок был недавно оживлён и снова получает критическое ранение в течение 2 минут, во второй раз его уже нельзя оживить. Если вы находитесь в критическом состоянии и не были оживлены в течение 5 минут, вы также окончательно погибаете. Если шансов на оживление нет, нажмите **Give up** на экране возрождения. После этого экран покажет, что вы мертвы, и вы сможете подготовиться к повторному появлению. Время ожидания перед нажатием Give up засчитывается в общее время возрождения.

### Re-spawning

Время возрождения игрока составляет минимум 45 секунд и максимум 60 секунд плюс временные штрафы. Время, проведённое в ожидании медика, вычитается из этого значения. После смерти игрок должен подождать не менее 5 секунд перед возрождением. На время возрождения влияют следующие действия:

* Смерть игрока: **+3 с**
* Захват контрольной точки или уничтожение цели: **−3 с**
* Выполнение оборонительного действия: **−1 с**
* Отряд построил передовой опорный пункт: **−10 с**

Временный штраф ко времени возрождения, который применяется только к следующей смерти (и может накапливаться до 5 минут), добавляется за следующие действия:

* Убийство союзника: **15 секунд за каждый тимкилл**
* Самоубийство: **15 секунд**
* Захват гражданского лица: **90 секунд**
* Убийство гражданского с нарушением ROE: **120 секунд за каждого гражданского**
* Уничтожение дружественного тайника с оружием: **300 секунд**

Чтобы выбрать точку возрождения, откройте карту возрождения (по умолчанию: **Enter**) и выберите доступное место, отмеченное белой точкой. После выбора точки необходимо нажать кнопку **Spawn** в правом нижнем углу экрана карты, чтобы вернуться в игру.

## _Logistics_ {#logistics}

Whether you're running low on ammunition and need to rearm, want a new kit or simply want to build deployables: logistics keep your team alive.

### Ammunition {#ammunition}

To be able to rearm yourself, you'll need to get closer to one of several sources of ammo, which will then automatically re-fill your weapons. These sources are:

* **Ammo bags** - These can be found in the rifleman, militant, warrior and some insurgent kits and must be thrown \(left click\) on the ground, for you or other soldiers be able to rearm, or on deployables \(tow, aa, mortars\) to rearm them. 
* **Ammo boxes** - Dropped by light transport vehicles, APCs and IFVs.
* **Light/Heavy supply crates** - Dropped primarily by transport or supply trucks \(also known as Logis\) and transport helicopters. For more information see [Supply Crates](the_basics.md#crates).
* **Weapons caches** - Available only for insurgents.
* **Vehicle depot** - Present in all main bases, it also heals you.

{% figure "../assets/ammobag.png", "../assets/supplycrate.png", "../assets/inscrate.png", "../assets/cacahe.png", "../assets/depott.png" %}
Ammunition bag, Coalition forces ammo crate, Insurgent forces ammo crate, weapon cache & Vehicle depot.
{% endfigure %}

Be aware that with the exception of **Weapons caches** and **Vehicle depot** all other ammo sources are **limited**. Eventually these sources will deplete and disappear. It is even possible ammo sources deplete before you're completly rearmed.
**Ammo bags**, **ammo boxes** and **supply crates** use **supply points** to determine how long they can be used. You can find out the remaining supply points of **supply crates** and **ammo boxes** by looking at it for a second. It will then appear next to the compass. 
The various weapons available in PR require different ammounts of supply points to be replenished. Utility items such as the grappling hook, tripflares and field dressings cost less to resupply per use than explosive ordnance such as anti-tank rockets/missiles, fragmentation grenades and mines. See below tables for the resupply cost of the corresponding weapon category and type:

<div style="text-align: center";>
<p><b>Firearms</b></div>

| **Type** | **Supply points cost** |
| --- | --- |
| **Pistols low capacity** | 15 |
| **Pistols high capacity** | 30 |
| **PDW** | 30 |
| **SMG** | 45 |
| **Shotgun primary** | 50 |
| **Shotgun breacher** | 25 |
| **Rifle** | 60 |
| **Sniper** | 40 |
| **LMG** | 150 |
| **GPMG** | 200 |

<div style="text-align: center";>
<p><b>Grenade Launcher/Rifle Grenades</b></div>

| **Type** | **Supply points cost** |
| --- | --- |
| **Anti-Tank x1** | 70 |
| **Anti-Tank x2** | 140 |
| **Flare** | 60 |
| **Fragmentation low capacity** | 80 |
| **Fragmentation high capacity** | 120 |
| **Smoke** | 60 |

<div style="text-align: center";>
<p><b>Items & Utilities</b></div>

| **Type** | **Supply points cost** |
| --- | --- |
| **Ammo box** | 200 |
| **C4 low capacity** | 45 |
| **C4 high capacity** | 75 |
| **Tripflare** | 20 |
| **Grappling hook** | 40 |
| **Epipen** | 60 |
| **Field dressing x1** | 30 |
| **Field dressing x3** | 75 |
| **Field dressing x6** | 120 |
| **Field dressing x12** | 180 |

<div style="text-align: center";>
<p><b>Heavy ordnance & munitions</b></div>

| **Type** | **Supply points cost** |
| --- | --- |
| **Fragmentation grenade x1** | 60 |
| **Fragmentation grenade x2** | 120 |
| **Fragmentation grenade x4** | 240 |
| **Smoke grenade low capacity** | 40 |
| **Smoke grenade high capacity** | 60 |
| **Signal smoke grenade** | 30 |
| **Anti-personel mine x2** | 140 |
| **Anti-personel mine x3** | 210 |
| **Conventional mine** | 420 |
| **Insurgent mine** | 160 |
| **Light IED** | 60 |
| **Heavy IED** | 80 |
| **Anti-air missile x1** | 100 |
| **Anti-air missile x2** | 170 |
| **Light anti-tank x1** | 70 |
| **Light anti-tank x2** | 140 |
| **Light anti-tank x3** | 210 |
| **Light anti-tank x4** | 280 |
| **Medium anti-tank x1** | 80 |
| **Medium anti-tank x2** | 160 |
| **Medium anti-tank x3** | 240 |
| **Heavy anti-tank x1** | 90 |
| **Heavy anti-tank x2** | 180 |
| **Guided anti tank** | 120 |

Note that on a local server the resupply system will not work as described. Every weapon slot will require 100 supply points to refill regardless of item type.

Requesting a kit costs 250 supply points. Be aware that re-arming an ammo bag at, for example, an ammo box or light/heavy supply crate will cost 200 points.
The amount of supply points for the supply sources are:

* **Ammo bags :** 205 \(will only count for 43 supply points when used by an asset emplacement like a TOW or mortar for example\).
* **Ammo boxes :** 500.
* **Light supply crates :** 1500.
* **Heavy supply crates :** 3000.

{% note %}
Resupplying is not instant but takes a few seconds, depending on the ammo source, as well as the amount of ammo you need to resupply. Additionally if you're not rearming, confirm that the Light/Heavy supply crate is indeed yours, rearming from enemy supply crates is not possible.
{% endnote %}

### Supply Crates{#crates}

There are two types of supply crates in PR:BF2 - Light Supply Crate and Heavy Supply Crate. While both allow to ressuply players and build deployables a Light crate is the equivalent of half of the Heavy Supply Crate, meaning that you will need 2x light supply crates where only 1x heavy supply crate is needed. To learn more about deployable emplacements see the 
[Deployable Structures chapter.](the_squad_leader.md#deployable-structures)

{% figure "../assets/largecrate.png", "../assets/smallcrate.png" %}
Here you can see the heavy supply crate on the left and the light version on the right.
{% endfigure %}

Just like rearming, requesting kits from crates will deplete the supply crates. Each kit will cost 250 points, with light crates having 1500 \(6x kits\) and heavy ones 3000 \(12x kits\).

{% note %}
Requesting kits from a crate that does not have enough points will still grant you the kit but the crate will be destroyed in the process.
{% endnote %}

Light Supply Crate can be transported by:

* Light Helicopters such as the Huey, Lynx and Zhi-9B \(One Crate\)
* Transport trucks \(One Crate\)

While, Heavy Supply Crate can be transported by:

* Medium Lift Helicopters such as the Black Hawk, Mi-17 and NH-90 \(One Crate\)
* Heavy Lift Helicopters such as the Chinook, Zhi-8KA and MV-22 \(Two Crates\)
* Logistic trucks \(Two Crates\)

The ownership of the crate is depicted by the flag display on top of the crate.

### Repair Drop

Logistic trucks also have the ability to drop a repair station. They are necessary for field repairs to vehicles that are heavily damaged and cannot move.

{% figure "../assets/reapir.png" %}
Repair drop.
{% endfigure %}

## _Score_ {#score}

A player's score is divided in teamwork points and individual points. It speaks for itself that doing team related activities \(building, driving vehicles, defending/attacking flags\) contribute to the first and individual actions \(killing players\) contribute to your personal score.

The total score of a player can never go below 0 but the teamwork score can become negative. There are also score multipliers for when you are for example in a vehicle or a squad leader. Here are some other score additions and deductions. These are not all but give you a good idea on what you can achieve.

* Capturing a civilian: **+100**
* Killing a civilian \(outside ROE\): **-100**
* Destroying your own objective: **-100**
* Destroying enemy objective: **+150**

## _Mortars_ {#mortars}

A fixed mortar position that can provide indirect fire support over long distances. All factions can fire high-explosive rounds. Conventional forces and the militia can also use air-burst and smoke rounds. Mortars cannot be constructed on maps smaller than 2km.

* **High Explosive \(HE\)** \(press **1** to select\): Most common type of mortar round. Does the most damage directly to the target. Ideal for light armored targets and emplacements.
* **Airburst** \(press **2** to select\): Explodes in the air above the ground. Covers a larger area but does less damage overall. Ideal for engaging infantry inside buildings and on uneven terrain.

Once mortars are constructed they need to be armed with ammo bags, provided by the rifleman or similar class. Then you can use the mortar’s calculator \(press **3** to select\). The distance to the target and the difference in elevation can be entered into the calculator by clicking on the numbers in the **“Range”** and **“Height”** fields. To get the range make sure your SL’s marker is on the target, then open the map and you’ll find the range listed under the map. Once you are done just click the **“Calculate”** button to display the required barrel elevation. The elevation can be adjusted with the W and S keys while the deflection is changed using the A and D keys. When both values are set, just select the required rounds and fire. The Airburst and Impact rounds share the same ammunition pool.

{% figure "../assets/mortars.png" %}
The mortar calculator interface.
{% endfigure %}

## _Destroying Bridges_ {#destroying-bridges}

Just like BF2, in PR you can destroy bridges. This is done with high capacity C4 or similar calibre explosives, carried by engineers or sapppers. 

When bridges get damaged particles and sound of falling sand can be observed when close by. Damaged further, segments of the bridge will collapse and neither infantry nor vehicles will be able to cross it. 

Unlike BF2, in PR once a bridge is destroyed, it can't be repaired. Therefore you should only destroy bridges that will change enemy team's routes in your favour - whether this is for delaying future movement or funneling enemy troops into a different part of the map.

{% figure "../assets/bridge_built_and_destroyed_small.png" %}
A bridge before and after being destroyed.
{% endfigure %}

On some destroyed bridges you can deploy a CSB, which will help you cross it \(covered in the [next chapteer](the_basics.md#close-support-bridges)\).

## _Close Support Bridges \(CSB\)_ {#close-support-bridges}

When in need to cross small rivers or damaged bridges, conventional forces can deploy CSBs using their logistic trucks - which carries two of them. In Project Reality CSBs can only be used to fill the gaps of destroyed bridges and in predetermined locations identified by \(obvious\) small heaps of sand positioned across a natural obstacle, like a river.

{% note %}
CSBs are very narrow, so drive carefully when crossing them.
{% endnote %}

The deployment process for CSBs is very simple:
1. Drive a logistics truck to the position where the CSB will be deployed.
2. Position the front or back of the truck as close as possible to the deployment position.
3. Select the CSB as active equipment of the truck.
4. Press alternate fire to deploy the bridge.

{{ "Video Tutorial - CSB Deployment" | youtube("Vn66KbNrVJA") }}

{% figure "../assets/csb.png" %}
CSB from truck being deployed.
{% endfigure %}

In some cases multiple CSBs are required to span the complete distance. In such situations, you're required to drive to the end of the incomplete bridge and deploy a new CSB and repeat until its finish.

You may encounter different scenarios when it comes to bridges and CSB deployment, shown in the next image:
1. This large concrete bridge is destroayble and a CSB can be deployed on it \(marked by a single bridge icon\).
2. This small rock bridge is destroyable but CSBs can't be deployed on it \(no bridge marking\).
3. And lastly at this location a double CSB can be deployed \(double bridge marking\).

{% figure "../assets/bridges2.png" %}
Different types of bridges (icons are not to scale).
{% endfigure %}

## _Battlefield Navigation_ {#battlefield-navigation}

It is pretty easy to get lost on the large maps of PR:BF2. The slow pacing and team coordination also requires players to communicate locations in a clear and concise manner. PR:BF2 offers 4 tools to aid players with this.

1. Squad leaders can use their **squad order marker** to communicate locations to their squad and the commander. The direction to the marker is indicated by a chevron above the compass. If you are within 75m of the marker you'll also see a 3D icon which shows the location in front of you. The marker will also be visible on the map.

{% figure "../assets/target.png", "../assets/build.png", "../assets/observe.png", "../assets/defendmarker.png", "../assets/demolish.png", "../assets/move.png" %}
Targe, build, observe, defend, demolish and move marker, respectively.
{% endfigure %}

1. A **precision degree compass** to the bottom central area of your screen. The compass can be used to give exact bearings of nearby spotted enemies. **The 8 Cardinal Directions** are clearly indicated along with the degree bearing labels which incrementally increase every 15° with major divisions every 5°. If you just want to communicate a general direction it is best practice to say the cardinal direction, followed by the degree and in some situations the distance if appropriate. For example _**“Enemy spotted NE 75° degrees 200 meters out”**_**.**
   * If the target is visually in line with a numbered bearing on your compass when you are facing that direction, you simply communicate that number.
   * Remember that all large compass notches equal 5 degrees. If the target is in line with a notch to the right of a labelled notch along from 75° then right you add 5°. So the target is at 80°.![](../assets/compass.png) 
   * Underneath the compass notches is a triangle which indicates your current bearing. If you are in a Squad, your Squad Leader’s last/currently issued order shows as a chevron as well. If you line up the chevron with the triangle, you’re looking at the location of the order mark.
2. The maps in PR:BF2 contain **grid reference labels and keypad subgrids**. The Grid labels are found on the upper and left border of the map. The map is divided into 169 grid squares starting with A1 in the upper left corner and ending with M13 in the lower right corner. Each grid square is divided in 9 subgrids. Those are labeled from 1 to 9 in the same manner as a computer's numpad are arranged. \(Top row from left to right 7, 8, 9\). You can communicate locations by giving out a grid reference. For a rough location you only say the main grid field \(e.g. D6\). For precise locations you also add the subgrid location \(e.g. D6-2\, which would be pronounced as Delta 6, keypad 2). Grid references are mostly used to communicate locations between squads. When using Mumble the first letter of the Grid reference is usually annunciated using the NATO phonetic alphabet. The codewords are Alpha, Bravo, Charlie, Delta, Echo, Foxtrot, Golf, Hotel, India, Juliett, Kilo, Lima, Mike, November, Oscar, Papa, Quebec, Romeo, Sierra, Tango, Uniform, Victor, Whiskey, X-ray, Yankee and Zulu
3. **The scale of each grid** square is displayed in the bottom right hand corner of the map. A 1km map will be indicated by a 75m grid squad, 150m for a 2km and 300m for a 4km map. You can easily estimate distances on the map using the grid squares. The squad leader's squad screen also displays the approximate distance to your current squad marker below the map of the battlefield.  


{% figure "../assets/grid.png" %}
{% endfigure %}

## _Basic Vehicle Information_ {#basic-vehicle-information}

Many vehicles behave quite differently compared to BF2 and require more advanced knowledge to operate. Since they also have very long spawn times \(up to 20 minutes\) it is vital to know how to keep them away from problematic situations. This part will focus on explaining vehicle types and how they influence the team. For more details on how to use vehicles see the [Operating Vehicles chapter](operating_vehicles.md#general-vehicle-information).

There are many vehicle types in PR:BF2 used as classification. This isn’t always directly in line with their Real Life counterpart due to gameplay reasons. The following list shows you the main classes of vehicles in PR:BF2:

* **Jeep:** small transport vehicles that not always fill the entire squad. Can always drop small ammo crates. Sometimes are fitted with machine guns nests.

![](../assets/jeep.png)

* **Civilian vehicles:** PR:BF2’s insurgent forces have access to a range of civilian cars and technicals mounted with machine guns, rocket-pods and SPG-9 recoilless rifles. They also have a flatbed with a mounted AA-gun, bomb trucks and bomb cars in their arsenal. 

![](../assets/civiliancars.png)

* **Truck:** come in both transport and logistic variants. The transport variant is capable of dropping 1 light supply crate and can fit an entire squad. The Logistic variant can only fit 2 soldiers and can drop 2 heavy supply crates, repair stations and Close Support Bridges.

![](../assets/truck.png)

* **Armored Personnel Carrier \(APC\):** large armored vehicles more often than not armed with heavy weaponry. Often do not possess the force to defeat other heavy armored targets such as IFVs and tanks but are the best of all vehicle types at assisting infantry. Can fit 2 crewman \(driver and gunner\) and up to 6 soldier passengers.

![](../assets/apc.png)

* **Infantry Fighting Vehicle \(IFV\):** Better armed and stronger than most APCs with often capabilities to defeat heavy armored targets using AT-Missiles. Are not always capable of transporting infantry. Under this category often also fall the recon-vehicles.

![](../assets/ifv.png)

* **Anti-Tank Missile Mounted Vehicle \(ATM\):** The name speaks for itself. These are vehicles armed with AT-missiles to destroy other armored vehicles. Cannot transport infantry.

![](../assets/atm.png)

* **Tank:** Our heaviest of armored vehicles. They come equipped with AP, HE and COAX weaponry.

![](../assets/tank.png)

* **Anti-Air Vehicle:** These are usually light armored vehicles with only the ability to take out enemy aircraft and helicopters. They can use missiles or/and heavy guns.

![](../assets/aavehicles.png)

* **Boat:** PR:BF2 has a variety of boats, both armed and un-armed.

![](../assets/boats.png)

* **Transport Helicopter:** These helicopters usually come equipped with door-guns for the mounted infantry to use. They are also capable of dropping heavy supply crates. There are light, medium and heavy transport choppers. See the section on [Supply Crates](the_basics.md#crates) to read on which variant has which crates available to it.

![](../assets/transheli.png)

* **Attack Helicopters:** These helicopters come equipped with machine-gun pods and a variety of rockets and missiles. There are light, medium and heavy variants. Under this category also fall recon helicopters with the ability to laze targets and use their thermal cameras. They are not always armed.

![](../assets/attackhelis.png)

* **Jets:** PR:BF2 has a wide variety of jets. There are light and heavy attack jets, fighter jets, bombers and fighter-bombers.

![](../assets/jets.png)

* All friendly vehicles are marked on the map with unique icons for easy identification \(See [Vehicle Icons](vehicle_icons.md)\).
* If a team vehicle asset is destroyed it incurs a ticket penalty:
  * Jeep or truck: **2 tickets**
  * Transport helicopter: **5 tickets**
  * APC/AAV/RECON: **5 tickets**
  * Tank or IFV: **10 tickets**
  * Jet or attack helicopter: **10 tickets**
* Vehicles are **Team Locked** and you cannot operate enemy vehicles of any kind.
* Vehicles can only **be entered from appropriate positions** on the hull.

{% figure "../assets/entrypoints.png" %}
Vehicle entry points can differ per vehicle. Look for hatches.
{% endfigure %}

* Normal soldiers are allowed to drive small unarmored vehicles such as jeeps, trucks and boats without the need for any specialized kit. If you require **a crewman or pilot kit** to operate a vehicle position, you will receive a warning message upon entering it and the screen will fade to black. If you do not exit the vehicle position within a few seconds, you will die.
* When exiting **a moving or burning vehicle** you will become wounded and possibly die. The faster the vehicle moves the greater the chance of death.
* **Destroying vehicle wrecks** does not influence score although a warning message states otherwise when shooting friendly wrecks.
* When manning **stationary or vehicle weapons** it takes a specific warm up time before they have the ability to fire:
  * MG: **5 seconds**
  * Anti-Air Missile: **5 seconds**
  * AT-emplacement: **10 seconds**
  * Armor main cannon: **30 seconds**
* Most Stationary AT-Weapons have optics with fixed zoom capability \(default: **X**\). Some of them even offer thermal optics \(default: hold **T**\).
* Exiting vehicles in mid-air and falling into water from high altitudes will injure you and may result in your death.
* Players can **request kits** from an APC’s/IFV’s entry position.
* Armored vehicles are more vulnerable when attacked from their flanks. The armor on the rear of the vehicle is the weakest. A single well-placed anti-tank projectile can disable or take them out.
* On public servers \(not in local gamemodes\) you can quickly switch to the next available free seat in a vehicle by pressing **F8**.
* When in a vehicle, you can see the information on the occupied seats in the bottom left of the the HUD. It shows only important crew seats as squared markers. This includes driver and gunner positions. Passenger seats do not have such markers and are shown as a seperate counter.

{% figure "../assets/seaticons.png" %}
Important crew members are shown as squared markers. Passengers use a total counter above the vehicle icon.
{% endfigure %}
