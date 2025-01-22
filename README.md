![eisbison banner](./Images/TOR_logo.png)
<p align="center"><a href="https://github.com/Eisbison/TheOtherRoles/releases/"><img src="https://badgen.net/github/release/eisbison/theotherroles"></a></p>


| Impostor | Crewmate | Neutral | Modifier | Gamemode |
|----------|-------------|-----------------|----------------|----------------|
| [Godfather (Mafia)](#mafia) | [Mayor](#mayor) | [Jester](#jester) | [Bloody](#bloody) | [Classic](#roles) |
| [Mafioso (Mafia)](#mafia) | [Engineer](#engineer) | [Arsonist](#arsonist) | [Anti Teleport](#anti-teleport) | [Guesser Modifier](#guesser-modifier) |
| [Janitor (Mafia)](#mafia) | [Sheriff](#sheriff) | [Jackal](#jackal) | [Tie Breaker](#tie-breaker) | [Hide 'n' Seek](#hide-n-seek) |
| [Morphling](#morphling) | [Deputy](#deputy) | [Sidekick](#sidekick) | [Bait](#bait) | [Vanilla Hide 'n' Seek](https://www.innersloth.com/new-game-mode-hide-n-seek-is-here-emergency-meeting-35/) |
| [Camouflager](#camouflager) | [Lighter](#lighter) | [Vulture](#vulture) | [Lovers](#lovers) | [PropHunt](#prophunt)|
| [Vampire](#vampire) | [Detective](#detective) | [Lawyer](#lawyer) | [Sunglasses](#sunglasses) |
| [Eraser](#eraser) | [Time Master](#time-master) | [Prosecutor](#prosecutor) | [Mini](#mini) |
| [Trickster](#trickster) | [Medic](#medic) | [Pursuer](#pursuer) | [VIP](#vip) |
| [Cleaner](#cleaner) | [Swapper](#swapper) | [Thief](#thief) | [Invert](#invert) |
| [Warlock](#warlock) | [Seer](#seer) |  | [Chameleon](#chameleon) |
| [Bounty Hunter](#bounty-hunter) | [Hacker](#hacker) |  | [Shifter](#shifter)
| [Witch](#witch) | [Tracker](#tracker) |  | [Armored](#armored) |
| [Ninja](#ninja) | [Snitch](#snitch) |  |  |
| [Bomber](#bomber) | [Spy](#spy) |  |  |
| [Yo-Yo](#yoyo) | [Portalmaker](#portalmaker) |  |  |
| [Evil Guesser](#guesser) | [Security Guard](#security-guard) |  |  |
|  | [Medium](#medium) |  |  |
|  | [Trapper](#trapper) |  |  |
|  | [Nice Guesser](#guesser) |  |  |

The [Role Assignment](#role-assignment) section explains how the roles are being distributed among the players.


# Colors
**Lưu ý:** Màu sắc sáng và tối không còn phụ thuộc vào màu sắc của người chơi nữa. Thay vào đó, chúng được phân phối luân phiên sao cho luôn được cân bằng trong một phòng chơi.

Xin gửi lời cảm ơn lớn đến Avlona & Listoric vì đã sắp xếp màu sắc theo thứ tự tốt nhất có thể (một công việc không hề dễ dàng)!

![TOR Colors](./Images/TOR_colors.jpg)

# Roles

## Role Assignment

First you need to choose how many special roles of each kind (Impostor/Neutral/Crewmate) you want in the game.
The count you set will only be reached, if there are enough Crewmates/Impostors in the game and if enough roles are set to be in the game (i.e. they are set to > 0%). The roles are then being distributed as follows:
- First all roles that are set to 100% are being assigned to arbitrary players.
- After that each role that has 10%-90% selected adds 1-9 tickets to a ticket pool (there exists a ticket pool for Crewmates, Neutrals and Impostors). Then the roles will be selected randomly from the pools as long it's possible (until the selected number is reached, until there are no more Crewmates/Impostors or until there are no more tickets). If a role is selected from the pool, obviously all the tickets of that role are being removed.
- The Mafia, Lovers and Mini are being selected independently (without using the ticket system) according to the spawn chance you selected. After that the Crewmate, Neutral and Impostor roles are selected and assigned in a random order.

**Example:**\
Settings: 2 special Crewmate roles, Snitch: 100%, Hacker: 10%, Tracker: 30%\
Result: Snitch is assigned, then one role out of the pool [Hacker, Tracker, Tracker, Tracker] is being selected\
Note: Changing the settings to Hacker: 20%, Tracker: 60% would statistically result in the same outcome .


## Mafia
### **Team: Impostors**
Mafia là một nhóm gồm ba Impostors.\
The Godfather hoạt động như một Impostor bình thường.\
The Mafioso là một Impostor không thể giết cho đến khi The Godfather chết.\
The Janitor là một Impostor không thể giết, nhưng họ có thể ẩn xác chết thay vào đó.\

**LƯU Ý:**  

- Cần phải kích hoạt 3 Impostors để mafia xuất hiện.

### Game Options
| Name | Description |
|----------|:-------------:|
| Mafia Spawn Chance | -
| Janitor Cooldown | -
-----------------------

## Morphling
### **Team: Impostors**
Morphling là một Impostor có thể quét thêm ngoại hình của một người chơi.\
Sau một khoảng thời gian bất kỳ, họ có thể sử dụng ngoại hình đó trong một khoảng thời gian cố định, có thể thay đổi trong phần tùy chọn.\
\
**LƯU Ý:**  
- Kích thước của họ thu nhỏ lại bằng kích thước của Mini khi sao chép diện mạo.  
- Hacker có thể thấy màu mới trên bàn quản trị.  
- Màu của dấu chân cũng thay đổi tương ứng (bao gồm cả những dấu chân đã có sẵn trên mặt đất).  
- Các Impostor khác vẫn thấy rằng họ là Impostor (tên vẫn giữ nguyên màu đỏ).  
- Chỉ báo khiên cũng thay đổi tương ứng (Morphling có thể có hoặc mất chỉ báo khiên).  
- Mũi tên Tracker vẫn hoạt động.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Morphling Spawn Chance | -
| Morphling Cooldown | -
| Morph Duration | Time the Morphling stays morphed
-----------------------

## Camouflager
### **Team: Impostors**
Camouflager là một Impostor có khả năng kích hoạt chế độ ngụy trang.\
Chế độ ngụy trang kéo dài trong x-giây (có thể tùy chỉnh), và trong thời gian này, tên/pet/mũ của tất cả người chơi\
sẽ bị ẩn và mọi người chơi đều có cùng màu sắc.\
\
**LƯU Ý:**  
- Mini sẽ trông giống như tất cả người chơi khác.  
- Màu của dấu chân chuyển sang màu xám (bao gồm cả những dấu chân đã có sẵn trên mặt đất).  
- Hacker sẽ thấy các biểu tượng xám trên bàn quản trị.  
- Khiên sẽ không còn hiển thị nữa.  
- Mũi tên Tracker vẫn hoạt động.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Camouflager Spawn Chance | -
| Camouflager Cooldown | -
| Camo Duration | Time players stay camouflaged
-----------------------

## Vampire
### **Team: Impostors**
Vampire là một Impostor có khả năng cắn người chơi khác. Những người chơi bị cắn sẽ chết sau một khoảng thời gian có thể cấu hình.\
Nếu tỷ lệ xuất hiện của Vampire lớn hơn 0 (ngay cả khi không có Vampire trong trò chơi), tất cả người chơi có thể đặt một củ tỏi.\
Nếu nạn nhân ở gần một củ tỏi, nút "Bite Button" sẽ chuyển thành nút "Kill Button" mặc định và Vampire chỉ có thể thực hiện một cú giết bình thường.\
\
**LƯU Ý:**  
- Nếu một người chơi bị cắn vẫn còn sống khi một cuộc họp được gọi, họ sẽ chết ngay khi cuộc họp bắt đầu.  
- Thời gian hồi chiêu giống như thời gian hồi chiêu giết mặc định (+ thời gian trễ giết nếu Vampire cắn mục tiêu).  
- Nếu có một Vampire trong trò chơi, sẽ không có Warlock.  
- Nếu Vampire cắn một người chơi và Thief giết Vampire, cú cắn vẫn sẽ được thực hiện, nhưng Vampire mới sẽ được hiển thị trong hoạt ảnh giết.  
- Nếu Vampire cắn một người chơi và bị giết trước khi cú cắn được thực hiện, người chơi bị cắn sẽ sống sót.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Vampire Spawn Chance | -
| Vampire Kill Delay | -
| Vampire Cooldown | Sets the kill/bite cooldown
| Vampire Can Kill Near Garlics | The Vampire can never bite when their victim is near a garlic. If this option is set to true, they can still perform a normal kill there.
-----------------------

## Eraser
### **Team: Impostors**
Eraser là một Impostor có khả năng xóa vai trò của mọi người chơi.\
Những người chơi bị nhắm đến sẽ mất vai trò của họ sau cuộc họp, ngay trước khi một người chơi bị tẩy chay.\
Sau mỗi lần xóa, thời gian hồi chiêu sẽ tăng thêm 10 giây.\
Việc xóa sẽ được thực hiện, ngay cả khi Eraser hoặc mục tiêu của họ chết trước cuộc họp tiếp theo.\
Mặc định, Eraser có thể xóa mọi người trừ Spy và các Impostor khác.\
Tùy theo các tùy chọn, họ cũng có thể xóa những người này (Impostor sẽ mất khả năng đặc biệt của Impostor).\
\
**LƯU Ý:**  
- Shift của Shifter luôn được kích hoạt trước khi xóa (do đó vai trò mới của Shifter sẽ bị xóa hoặc Shifter sẽ lưu vai trò của mục tiêu, tùy vào người mà Eraser đã xóa).  
- Vì việc xóa được kích hoạt trước khi một người chơi bị tẩy chay, chiến thắng của Jester sẽ không xảy ra, vì việc xóa sẽ xảy ra trước.  
- Các Modifier sẽ không bị xóa.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Eraser Spawn Chance | -
| Eraser Cooldown | The Eraser's cooldown will increase by 10 seconds after every erase.
| Eraser Can Erase Anyone | If set to false, they can't erase the Spy and other Impostors
-----------------------

## Trickster
### **Team: Impostors**
Trickster là một Impostor có khả năng đặt 3 hộp jack-in-the-box ban đầu vô hình đối với các người chơi khác.\
Nếu Trickster đã đặt đủ số hộp, chúng sẽ được chuyển thành một mạng lưới ống thông hơi chỉ có thể sử dụng bởi chính Trickster, nhưng các hộp sẽ được lộ ra với những người chơi khác.\
Khi các hộp được chuyển thành mạng ống thông hơi, Trickster có được một khả năng mới "Lights out" để hạn chế tầm nhìn của Non-Impostors, và khả năng này không thể được sửa chữa bởi các người chơi khác. Đèn sẽ tự động được phục hồi sau một thời gian.\
\
**LƯU Ý:**  
- Impostors sẽ nhận được một chỉ báo văn bản ở dưới màn hình để thông báo cho họ nếu đèn bị tắt do khả năng của Trickster, vì không có mũi tên phá hoại hoặc văn bản nhiệm vụ phá hoại nào để thông báo cho họ về điều này.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Trickster Spawn Chance | -
| Trickster Box Cooldown | Cooldown for placing jack-in-the-boxes
| Trickster Lights Out Cooldown | Cooldown for their "lights out" ability
| Trickster Lights Out Duration | Duration after which the light is automatically restored
-----------------------

## Cleaner
### **Team: Impostors**
Cleaner là một Impostor có khả năng dọn xác chết.\
\
**LƯU Ý:**  
- Thời gian hồi chiêu giết và dọn xác được chia sẻ, ngăn không cho họ dọn xác ngay sau khi giết.  
- Nếu có một Cleaner trong trò chơi, sẽ không có Vulture.

### Game Options
| Name | Description |
|----------|:-------------:|
| Cleaner Spawn Chance | -
| Cleaner Cooldown | Cooldown for cleaning dead bodies
-----------------------

## Warlock
### **Team: Impostors**
Warlock là một Impostor có khả năng nguyền rủa một người chơi khác (người bị nguyền rủa không nhận thông báo).\
Nếu người bị nguyền rủa đứng gần một người chơi khác, Warlock có thể giết người chơi đó (bất kể khoảng cách).\
Việc thực hiện một cú giết với sự trợ giúp của người bị nguyền rủa sẽ làm gỡ bỏ lời nguyền và khiến Warlock không thể di chuyển trong một khoảng thời gian có thể cấu hình.\
Warlock vẫn có thể thực hiện những cú giết bình thường, nhưng hai nút giết này chia sẻ cùng một thời gian hồi chiêu.\
\
**LƯU Ý:**  
- Warlock luôn có thể giết các đồng đội Impostor của mình (và thậm chí giết chính mình) bằng cú "cursed kill".  
- Nếu có một Warlock trong trò chơi, sẽ không có Vampire.  
- Việc thực hiện một cú giết bình thường không gỡ bỏ lời nguyền.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Warlock Spawn Chance | -
| Warlock Cooldown | Cooldown for using the Curse and curse Kill
| Warlock Root Time | Time the Warlock is rooted in place after killing using the curse
-----------------------

## Bounty Hunter
### **Team: Impostors**
Bounty Hunter là một Impostor, liên tục nhận tiền thưởng (người chơi bị nhắm đến không nhận thông báo).\
Mục tiêu của Bounty Hunter sẽ thay đổi sau mỗi cuộc họp và sau một khoảng thời gian có thể cấu hình.\
Nếu Bounty Hunter giết mục tiêu của mình, thời gian hồi chiêu giết sẽ ngắn hơn rất nhiều so với bình thường.\
Việc giết một người chơi không phải mục tiêu hiện tại sẽ làm tăng thời gian hồi chiêu giết.\
Tùy theo các tùy chọn, sẽ có một mũi tên chỉ về phía mục tiêu hiện tại.\
\
**LƯU Ý:**  
- Mục tiêu sẽ không phải là một Impostor, một Spy hoặc Lover của Bounty Hunter.  
- Việc giết mục tiêu sẽ đặt lại thời gian hẹn giờ và một mục tiêu mới sẽ được chọn.  

### Game Options
| Name | Description |
|----------|:-------------:|
| Bounty Hunter Spawn Chance | -
| Duration After Which Bounty Changes | -
| Cooldown After Killing Bounty | -
| Additional Cooldown After Killing Others | Time will be added to the normal impostor cooldown if the Bounty Hunter kills a not-bounty player
| Show Arrow Pointing Towards The Bounty | If set to true an arrow will appear (only visiable for the Bounty Hunter)
| Bounty Hunter Arrow Update Interval | Sets how often the position is being updated
-----------------------

## Witch
### **Team: Impostors**
Witch là một Impostor có khả năng casting phép thuật lên những người chơi khác.\
Trong cuộc họp tiếp theo, người chơi bị đánh dấu phép thuật sẽ được làm nổi bật và họ sẽ chết ngay sau khi cuộc họp kết thúc.\
Có nhiều tùy chọn được liệt kê dưới đây để bạn có thể cấu hình theo sở thích của mình.\
Tương tự như Vampire, khiên và blank sẽ được kiểm tra hai lần (vào cuối quá trình casting phép thuật lên người chơi và vào cuối cuộc họp, khi phép thuật sẽ được kích hoạt).\
Điều này có thể khiến người chơi bị đánh dấu là bị phép thuật trong cuộc họp, nhưng không chết cuối cùng (khi họ có khiên hoặc Witch bị blank sau khi đã cast phép thuật lên người chơi).\
Nếu Witch chết trước khi cuộc họp bắt đầu hoặc nếu Witch bị đoán trong cuộc họp, những người chơi bị phép thuật sẽ được làm nổi bật nhưng họ sẽ sống sót trong mọi trường hợp.\
Tùy theo các tùy chọn, bạn có thể chọn xem việc tẩy chay Witch có cứu tất cả những người bị phép thuật hay không.\
\
**LƯU Ý:**  
- Những người chơi bị phép thuật sẽ chết trước khi người chơi bị tẩy chay chết (điều này có thể kích hoạt, ví dụ, một điều kiện chiến thắng Impostor, ngay cả khi Witch là người bị tẩy chay).

### Game Options
| Name | Description |
|----------|:-------------:|
| Witch Spawn Chance | -
| Witch Spell Casting Cooldown | -
| Witch Additional Cooldown | The spell casting cooldown will be increased by the amount you set here after each spell
| Witch Can Spell Everyone | If set to false, the witch can't spell the Spy and other Impostors
| Witch Spell Casting Duration | The time that you need to stay next to the target in order to cast a spell on it
| Trigger Both Cooldowns | If set to true, casting a spell will also trigger cooldown of the kill button and vice versa (but the two cooldowns may vary)
| Voting The Witch Saves All The Targets | If set to true, all the cursed targets will survive at the end of the meeting
-----------------------

## Ninja
### **Team: Impostors**
Ninja là một Impostor có khả năng giết một người chơi ở bất kỳ đâu trên bản đồ.\
Bạn có thể đánh dấu một người chơi với khả năng của mình và bằng cách sử dụng khả năng này lần nữa, bạn sẽ nhảy đến vị trí của người chơi bị đánh dấu và giết họ.\
Tùy theo các tùy chọn, bạn sẽ biết vị trí của người chơi bị đánh dấu.\
Khi Ninja sử dụng khả năng, nó sẽ để lại dấu vết (lá) trong một khoảng thời gian có thể cấu hình, nơi nó kích hoạt khả năng và thêm vào đó là nơi nó giết người chơi bị đánh dấu trước đó.\
Khi thực hiện cú giết bằng khả năng Ninja, Ninja có thể trở nên vô hình trong vài giây (tùy theo các tùy chọn).\
\
**LƯU Ý:**  
- Ninja có thời gian hồi chiêu 5 giây sau khi đánh dấu một người chơi.  
- Dấu vết có màu tối (đen) hoặc sáng (trắng) tùy thuộc vào màu sắc của người chơi, và sẽ phai dần thành màu xanh lá cây.  
- Dấu đánh dấu trên người chơi bị đánh dấu sẽ bị đặt lại sau một cuộc họp hoặc sau khi sử dụng khả năng để giết người chơi bị đánh dấu. Việc thực hiện một cú giết bình thường **KHÔNG** đặt lại dấu đánh dấu.  
- Nếu Ninja cố gắng giết một người chơi có khiên (ví dụ: khiên của Medic, khiên cuối trò chơi đầu tiên), cú giết sẽ không được thực hiện.  
- Nếu Ninja cố gắng giết Time Master trong khi khiên còn hoạt động, Ninja sẽ không dịch chuyển đến vị trí của người chơi, nhưng khiên của Time Master vẫn sẽ được kích hoạt.  
- Nếu mục tiêu bị đánh dấu ở một tầng khác trên bản đồ Submerged, mũi tên sẽ luôn chỉ về phía thang máy.

### Game Options
| Name | Description |
|----------|:-------------:|
| Ninja Spawn Chance | -
| Ninja Mark Cooldown | -
| Ninja Knows Location Of Target | -
| Trace Duration | -
| Time Till Trace Color Has Faded | -
| Time The Ninja Is Invisible | -
-----------------------

## Bomber
### **Team: Impostors**
Bomber là một Impostor có khả năng trở nên rất nổ. Họ có khả năng đặt bom để nhóm các Crewmates lại với nhau và giết họ.\
Bomber cũng có khả năng thực hiện một cú giết bình thường như tất cả Impostors.\
Thời gian đặt bom có thể khác với thời gian hồi chiêu giết tùy theo cài đặt.\
Crewmates có thể gỡ bom tùy theo cài đặt.  

**LƯU Ý:**  
- Bom sẽ không giết người chơi có khiên (Medic, First Kill Shield).  
- Bom sẽ không giết Mini cho đến khi nó phát triển.  
- Bom có thể giết chính Bomber và đồng đội của họ.  
- Phạm vi nghe có thể cao hơn/thấp hơn phạm vi phá hủy thực tế, tùy theo cài đặt, và có chỉ báo hình ảnh.  
- Chỉ báo hình ảnh dần dần chuyển sang màu đỏ cho đến khi bom nổ và không hiển thị phạm vi nổ (chỉ hiển thị phạm vi nghe)!  
- Bom có thể được gỡ bằng cách đứng trên nó và cắt ngòi (nút bấm).

### Game Options
| Name | Description |
|----------|:-------------:|
| Bomber Spawn Chance | -
| Bomb Destruction Time | -
| Bomb Destruction Range | -
| Bomb Hear Range | -
| Bomb Defuse Duration | -
| Bomb Cooldown | -
| Bomb Is Active After |
-----------------------

## YoYo
### **Team: Impostors**
Yo-Yo là một Impostor có khả năng đánh dấu một vị trí và sau đó nhảy (dịch chuyển) đến vị trí đó.\
Sau cú nhảy đầu tiên, Yo-Yo có một khoảng thời gian cố định (tùy chọn) để làm bất cứ điều gì họ muốn, trước khi tự động nhảy trở lại vị trí ban đầu của cú nhảy đầu tiên.\
Mỗi cú nhảy sẽ để lại một bóng mờ với độ trong suốt có thể cấu hình. Bóng mờ này rất khó nhìn thấy.\
Yo-Yo cũng có thể có quyền truy cập vào bảng quản trị di động, tùy theo cài đặt.

**LƯU Ý:**  
- Vị trí đánh dấu cho mục tiêu của cú nhảy đầu tiên chỉ hiển thị cho Yo-Yo và ma.  
- Bóng mờ của cú nhảy đầu tiên sẽ tồn tại (hầu như) cho đến khi Yo-Yo quay lại.  
- Bóng mờ của cú nhảy thứ hai (quay lại) sẽ tồn tại trong 5 giây.

### Game Options
| Name | Description |
|----------|:-------------:|
| Yo-Yo Spawn Chance | -
| Blink Duration | -
| Mark Location Cooldown | -
| Marked Location Stays After Meeting | -
| Has Admin Table | -
| Admin Table Cooldown | -
| Silhouette Visibility | -
-----------------------

## Guesser
### **Team: Crewmates or Impostors**
Guesser có thể là một Crewmate hoặc một Impostor (tùy theo cài đặt).\
Guesser có thể bắn những người chơi trong cuộc họp bằng cách đoán vai trò của họ. Nếu đoán sai, Guesser sẽ chết thay vào đó.\
Bạn có thể chọn số lượng người chơi có thể bị bắn trong mỗi trò chơi và liệu có thể bắn nhiều người chơi trong một cuộc họp hay không.\
Đoán Impostor và Crewmate chỉ đúng nếu người chơi là một phần của nhóm tương ứng và không có vai trò đặc biệt.\
Bạn chỉ có thể bắn trong thời gian bỏ phiếu.\
Tùy theo cài đặt, Guesser không thể đoán người chơi có khiên và tùy theo các tùy chọn của Medic, người Medic/người chơi có khiên có thể được thông báo (không ai sẽ chết, bất kể Guesser đoán gì).  

**LƯU Ý:**  
- Nếu một người chơi bị bắn, bạn sẽ nhận lại phiếu bầu của mình.  
- Điều kiện chiến thắng của Jester sẽ không được kích hoạt, nếu Guesser bắn Jester trước khi Jester bị tẩy chay.

### Game Options
| Name | Description |
|----------|:-------------:|
| Guesser Spawn Chance | -
| Chance That The Guesser Is An Impostor | -
| Guesser Number Of Shots Per Game | -
| Guesser Can Shoot Multiple Times Per Meeting |  -
| Guesses Visible In Ghost Chat | -
| Guesses Ignore The Medic Shield | -
| Evil Guesser Can Guess The Spy | -
| Both Guesser Spawn Rate | -
| Guesser Can't Guess Snitch When Tasks Completed | -

-----------------------

## Jester
### **Team: Neutral**
Jester không có bất kỳ nhiệm vụ nào. Họ sẽ chiến thắng trò chơi một mình nếu bị tẩy chay trong cuộc họp.

### Game Options
| Name | Description |
|----------|:-------------:|
| Jester Spawn Chance | -
| Jester Can Call Emergency Meeting | Option to disable the emergency button for the Jester
|Jester Has Impostor Vision | -
-----------------------

## Arsonist
### **Team: Neutral**
Arsonist không có bất kỳ nhiệm vụ nào, họ phải chiến thắng trò chơi một mình.\
Arsonist có thể tưới xăng lên các người chơi khác bằng cách nhấn nút douse và đứng cạnh người chơi đó trong vài giây.\
Nếu người chơi mà Arsonist tưới xăng ra ngoài phạm vi, thời gian hồi chiêu sẽ được đặt lại về 0.\
Sau khi tưới xăng lên tất cả những người chơi còn sống, Arsonist có thể kích hoạt lửa cho tất cả người chơi, dẫn đến chiến thắng của Arsonist.

### Game Options
| Name | Description |
|----------|:-------------:|
| Arsonist Spawn Chance | -
| Arsonist Cooldown | -
| Arsonist Douse Duration | The time it takes to douse a player
-----------------------

## Jackal
### **Team: Jackal**
Jackal là một phần của đội phụ, cố gắng loại bỏ tất cả các người chơi khác.\
Jackal không có nhiệm vụ và có thể giết Impostors, Crewmates và Neutrals.\
Jackal (nếu được phép theo cài đặt) có thể chọn một người chơi khác làm Sidekick của họ.\
Việc tạo Sidekick sẽ loại bỏ tất cả nhiệm vụ của Sidekick và thêm họ vào đội Jackal. Sidekick sẽ mất vai trò hiện tại của mình (trừ khi họ là Lover, thì họ chơi trong hai đội).\
Hành động "Tạo Sidekick" chỉ có thể sử dụng một lần mỗi Jackal hoặc một lần mỗi trò chơi (tùy theo cài đặt).\
Jackal cũng có thể thăng cấp Impostors thành Sidekick của mình, nhưng tùy theo cài đặt, Impostor sẽ thực sự biến thành Sidekick và rời đội Impostors, hoặc họ chỉ trông giống như Sidekick đối với Jackal và vẫn giữ nguyên vai trò của mình.\
Ngoài ra, nếu Spy hoặc Impostor bị chọn làm Sidekick, họ vẫn sẽ xuất hiện màu đỏ đối với Impostors.

Đội Jackal tạo ra nhiều kết quả mới cho trò chơi, ví dụ:
- Impostors có thể bị loại bỏ và sau đó Crew đấu với đội Jackal.
- Crew có thể bị loại bỏ, sau đó đội Jackal đấu với Impostors (Crew vẫn có thể giành chiến thắng nhiệm vụ trong trường hợp này).

Ưu tiên của các điều kiện chiến thắng như sau:
1. Jester chiến thắng bằng cách bỏ phiếu (ngay cả khi là Mini).
2. Crewmate Mini thua bằng cách bỏ phiếu.
3. Arsonist chiến thắng.
4. Đội Impostor chiến thắng bằng cách phá hoại.
5. Đội Crew chiến thắng bằng nhiệm vụ (cũng có thể nếu tất cả Crew đã chết).
6. Lovers trong ba người chơi cuối cùng chiến thắng.
7. Đội Jackal chiến thắng bằng cách vượt số (Khi đội Jackal có số lượng người chơi bằng hoặc lớn hơn đội Crew và không còn Impostors và đội Jackal không có Lover).
8. Đội Impostor chiến thắng bằng cách vượt số (Khi đội Impostors có số lượng người chơi bằng hoặc lớn hơn đội Crew và không còn người chơi nào của đội Jackal và đội Impostors không có Lover).
9. Đội Crew chiến thắng bằng cách vượt số (Khi không còn người chơi nào của đội Jackal và đội Impostors).

**LƯU Ý:**  
- Jackal (và Sidekick của họ) có thể bị giết bởi Sheriff.  
- Jackal không thể nhắm mục tiêu Mini khi nó đang phát triển. Sau đó, họ có thể giết nó hoặc chọn nó làm Sidekick.  
- Đội Crew vẫn có thể chiến thắng, ngay cả khi tất cả thành viên của họ đã chết, nếu họ hoàn thành nhiệm vụ đủ nhanh (Đó là lý do việc chuyển Crewmate cuối cùng còn nhiệm vụ thành Sidekick dẫn đến chiến thắng nhiệm vụ cho Crew).

Nếu cả Impostors và Jackals đều có trong trò chơi, trò chơi sẽ tiếp tục ngay cả khi tất cả Crewmates đã chết. Crewmates vẫn có thể chiến thắng trong trường hợp này bằng cách hoàn thành nhiệm vụ. Jackal và Impostor phải giết nhau.

### Game Options
| Name | Description
|----------|:-------------:|
| Jackal Spawn Chance | -
| Jackal/Sidekick Kill Cooldown | Kill Cooldown
| Jackal Create Sidekick Cooldown | Cooldown before a Sidekick can be created
| Jackal Can Use Vents | Yes/No
| Jackal Can Sabotage Lights | Yes/No
| Jackal Can Create A Sidekick | Yes/No
| Sidekick Gets Promoted To Jackal On Jackal Death | Yes/No
| Sidekick Can Kill | Yes/No
| Sidekick Can Vent | Yes/No
| Sidekick Can Sabotage Lights | Yes/No
| Jackals Promoted From Sidekick Can Create A Sidekick | Yes/No (to prevent the Jackal team from growing)
| Jackals Can Make An Impostor To His Sidekick | Yes/No (to prevent a Jackal from turning an Impostor into a Sidekick, if they use the ability on an Impostor they see the Impostor as Sidekick, but the Impostor isn't converted to Sidekick. If this option is set to "No" Jackal and Sidekick can kill each other.)
| Jackal And Sidekick Have Impostor Vision | -
-----------------------

## Sidekick
### **Team: Jackal**
Được chỉ định cho một người chơi trong suốt trò chơi bởi "Hành động Tạo Sidekick" của Jackal và gia nhập Jackal trong nhiệm vụ loại bỏ tất cả các người chơi khác.\
Khi Jackal chết (tùy theo cài đặt), họ có thể được thăng cấp thành Jackal và thậm chí có thể chỉ định một Sidekick của riêng mình.

**LƯU Ý:**
- Một người chơi chuyển thành Sidekick sẽ mất vai trò và nhiệm vụ trước đó (nếu họ có).
- Sidekick có thể bị giết bởi Sheriff.
- Sidekick không thể nhắm mục tiêu Mini khi nó đang phát triển.

### Game Options
| Name | Description
|----------|:-------------:|
| Jackal/Sidekick Kill Cooldown | Uses the same kill cooldown setting as the Jackal |
| Sidekick Gets Promoted To Jackal On Jackal Death |  Yes/No |
| Sidekick Can Kill | Yes/No |
| Sidekick Can Use Vents | Yes/No |
-----------------------

## Vulture
### **Team: Neutral**
Vulture không có nhiệm vụ, họ phải chiến thắng trò chơi như một cá nhân.\
Vulture là một vai trò trung lập, phải ăn một số xác chết nhất định (tùy theo cài đặt) để chiến thắng.\
Tùy vào cài đặt, khi một người chơi chết, Vulture sẽ nhận được một mũi tên chỉ tới xác chết.\
Nếu có Vulture trong trò chơi, sẽ không có Cleaner.

**LƯU Ý:**
- Nếu xác chết ở một tầng khác trên bản đồ Submerged, mũi tên sẽ luôn chỉ tới thang máy.

### Game Options
| Name | Description |
|----------|:-------------:|
| Vulture Spawn Chance | -
| Vulture Countdown | -
| Number Of Corpses Needed To Be Eaten | Corpes needed to be eaten to win the game
| Vulture Can Use Vents | -
| Show Arrows Pointing Towards The Corpes | -
-----------------------

## Lawyer
### **Team: Neutral**
Lawyer là một vai trò trung lập có một khách hàng.\
Khách hàng có thể là Impostor hoặc Jackal (không phải Lover).\
Tùy vào cài đặt, khách hàng cũng có thể là Jester.\
Lawyer cần khách hàng của mình chiến thắng để chiến thắng trò chơi.\
Khách hàng không biết rằng mình là khách hàng của Lawyer.\
Nếu khách hàng của Lawyer bị loại, Lawyer sẽ chết cùng với khách hàng.\
Nếu khách hàng của Lawyer chết, Lawyer sẽ thay đổi vai trò và trở thành [Pursuer](#pursuer), với mục tiêu khác để chiến thắng trò chơi.

Cách Lawyer chiến thắng:
- Lawyer sống/chết, khách hàng sống và khách hàng chiến thắng: Lawyer chiến thắng cùng đội của khách hàng.
- Nếu khách hàng là Jester và Jester bị loại, Lawyer chiến thắng cùng với Jester.

**LƯU Ý:**
- Nếu khách hàng ngắt kết nối, Lawyer cũng sẽ trở thành Pursuer.
- Lawyer cần phải tìm ra vai trò của khách hàng tùy vào cài đặt.
- Nhiệm vụ chỉ được tính nếu Lawyer được thăng cấp thành Pursuer.
- Nếu Lawyer chết trước khách hàng của mình, họ sẽ mất tất cả nhiệm vụ và sẽ ngay lập tức có tầm nhìn tổng quan.

### Game Options
| Name | Description |
|----------|:-------------:|
| Lawyer Spawn Chance | -
| Chance That The Lawyer Is Prosecutor | -
| Lawyer/Prosecutor Vision | Pursuer has normal vision
| Lawyer/Prosecutor Knows Target Role | -
| Lawyer/Prosecutor Can Call Emergency Meeting | -
| Lawyer Target Can Be The Jester | -
-----------------------

## Prosecutor
### **Team: Neutral**
Prosecutor là một vai trò trung lập giống như Lawyer. Prosecutor có một khách hàng là Crewmate.\
Prosecutor cần khách hàng của mình bị loại để chiến thắng trò chơi.\
Khách hàng của Prosecutor không biết rằng mình là khách hàng của Prosecutor.\
Nếu khách hàng bị sidekicked, Prosecutor sẽ thay đổi vai trò và trở thành [Lawyer](#lawyer) của khách hàng và phải bảo vệ khách hàng từ bây giờ.\
Nếu khách hàng của Prosecutor chết, Prosecutor sẽ thay đổi vai trò và trở thành [Pursuer](#pursuer), với mục tiêu khác để chiến thắng trò chơi.

**LƯU Ý:**
- Cài đặt vai trò của Prosecutor được chia sẻ với cài đặt của Lawyer.
- Nếu khách hàng ngắt kết nối, Prosecutor cũng sẽ trở thành Pursuer.
- Prosecutor cần phải tìm ra vai trò của khách hàng tùy vào cài đặt.
- Nhiệm vụ chỉ được tính nếu Prosecutor được thăng cấp thành Pursuer.
- Nếu Prosecutor chết trước khách hàng của mình, họ sẽ mất tất cả nhiệm vụ và sẽ ngay lập tức có tầm nhìn tổng quan.

## Pursuer
### **Team: Neutral**
Pursuer là một vai trò trung lập với điều kiện chiến thắng đặc biệt. Họ phải sống sót cho đến khi trò chơi kết thúc và phe Crew chiến thắng. Để đạt được mục tiêu này, Pursuer có khả năng gọi là "Blank", cho phép họ làm hỏng vũ khí của kẻ giết người (bao gồm cả Sheriff). Khi được kích hoạt, "Blank" khiến kẻ giết người bỏ lỡ mục tiêu của họ, và thời gian hồi chiêu của họ sẽ được kích hoạt như bình thường.

**Các tính năng chính:**
- **Khả năng Blank:** Khi sử dụng, vũ khí của kẻ giết người sẽ bị trục trặc, khiến họ bỏ lỡ mục tiêu. Điều này cũng áp dụng với Sheriff. Khi sử dụng "Blank", khiên của các vai trò như Medic hoặc Time Master sẽ không được kích hoạt.
- **Nhiệm vụ:** Pursuer có nhiệm vụ có thể giúp đội Crew chiến thắng bằng cách hoàn thành các nhiệm vụ. Nếu Pursuer chết, các nhiệm vụ của họ sẽ không còn được tính cho chiến thắng nhiệm vụ.
- **Điều kiện chiến thắng:** Mục tiêu của Pursuer là sống sót trong khi đội Crew chiến thắng, tức là họ phải sống sót lâu hơn những người chơi còn lại trong khi đội Crew hoàn thành nhiệm vụ hoặc áp đảo những kẻ Impostors còn lại.

Vai trò này được thiết kế để hỗ trợ đội Crew trong những tình huống quan trọng bằng cách ngăn chặn một số vụ giết người, làm cho Pursuer trở thành một vai trò chiến lược giúp bảo vệ sự thành công của đội Crew trong khi đảm bảo sự sống sót của chính họ.
### Game Options
| Name | Description |
|----------|:-------------:|
| Pursuer Blank Cooldown | -
| Pursuer Number Of Blanks | -
-----------------------

## Thief
### **Team: Neutral**
**Thief** là một vai trò trung lập với điều kiện chiến thắng đặc biệt. Thief cần phải giết một kẻ giết người khác (Impostor, Jackal/Sidekick, và nếu được bật, cả Sheriff) để có thể đạt được điều kiện chiến thắng. Nếu Thief không giết được một kẻ giết người, họ sẽ thua cuộc.

Khi Thief giết một trong những kẻ giết người khác, Thief sẽ chiếm lấy vai trò của họ (ví dụ: Ninja) và gia nhập đội của họ (ví dụ: đội Impostor). Sau đó, Thief sẽ có điều kiện chiến thắng của vai trò mới đó (ví dụ: chiến thắng của Impostor).

Nếu Thief cố gắng giết một vai trò không phải là kẻ giết người (Crewmate hoặc Neutral), họ sẽ chết giống như một Sheriff bắn sai mục tiêu.

**Các tính năng chính:**
- **Giết kẻ giết người:** Thief phải giết một kẻ giết người (Impostor, Jackal/Sidekick hoặc Sheriff) để có thể có điều kiện chiến thắng. Nếu giết được, Thief sẽ chiếm lấy vai trò của kẻ giết người và gia nhập đội của họ.
- **Giết sai mục tiêu:** Nếu Thief cố gắng giết một vai trò không phải kẻ giết người (Crewmate hoặc Neutral), họ sẽ chết giống như một Sheriff bắn sai mục tiêu.
- **Tùy chọn "Thief Can Kill Sheriff":** Nếu tùy chọn này được bật, Thief có nhiệm vụ, nhưng nhiệm vụ này chỉ bắt đầu có giá trị khi Thief giết được Sheriff. Nếu không giết Sheriff, nhiệm vụ của Thief sẽ không được tính vào chiến thắng nhiệm vụ.
- **Tùy chọn "Thief Can Kill Sheriff" là Tắt:** Nếu tùy chọn này bị tắt, Thief sẽ không có nhiệm vụ nào.
- **Giết Witch:** Nếu Thief giết Witch, những người chơi đã bị Witch đánh dấu sẽ vẫn bị Witch đánh dấu (ngoại trừ Thief).

**Lưu ý:** Nếu Thief có thể đoán để "steal" vai trò, việc đoán Witch có thể cứu tất cả các mục tiêu hoặc không cứu ai (tùy vào cách thiết lập Witch).
### Game Options
| Name | Description |
|----------|:-------------:|
| Thief Spawn Chance | -
| Thief Countdown | -
| Thief Can Kill Sheriff | -
| Thief Has Impostor Vision | -
| Thief Can Use Vents | -
| Thief Can Guess To Steal Role | -
-----------------------

## Mayor
### **Team: Crewmates**
**The Mayor** là một vai trò trong nhóm Crewmate, có khả năng lãnh đạo và tăng cường quyền lực trong các cuộc họp. Vai trò này có các đặc điểm sau:

- **Bầu cử gấp đôi:** Mayor có một lá phiếu có giá trị gấp đôi trong các cuộc họp. Điều này có nghĩa là mỗi lá phiếu của Mayor sẽ đóng góp 2 phiếu thay vì 1, giúp ảnh hưởng mạnh mẽ hơn đến kết quả cuộc họp.
- **Sử dụng cuộc họp:** Mayor có thể sử dụng quyền họp của mình bất kể số lượng cuộc họp đã đạt đến mức tối đa. Điều này có nghĩa là ngay cả khi số cuộc họp đã hết, Mayor vẫn có thể yêu cầu một cuộc họp mới.
- **Nút họp di động:** Tùy vào các thiết lập, Mayor có thể có một nút họp di động, cho phép họ triệu tập một cuộc họp từ bất cứ đâu trong game.
- **Xem màu phiếu:** Sau khi hoàn thành một số nhiệm vụ nhất định (tùy theo cài đặt), Mayor có thể nhìn thấy màu phiếu của các người chơi khác trong cuộc họp, giúp họ có cái nhìn rõ ràng hơn về sự ủng hộ hoặc phản đối trong cuộc bầu cử.
- **Lựa chọn phiếu đơn:** Tùy vào các cài đặt, Mayor có thể có tùy chọn bỏ một phiếu thay vì hai phiếu (thông qua một nút trong màn hình cuộc họp), tùy theo chiến lược của họ trong cuộc họp.

**Lưu ý:** Mayor có thể sử dụng các quyền của mình để tác động đến kết quả của cuộc họp và giúp nhóm Crewmate đạt được chiến thắng trong những tình huống quan trọng.

### Game Options
| Name | Description |
|----------|:-------------:|
| Mayor Spawn Chance | -
| Mayor Can See Vote Colors | -
| Completed Tasks Needed To See Vote Colors | -
| Mobile Emergency Button | -
| Mayor Can Choose Single Vote | Off, On (Before Voting), On (Until Meeting Ends)
-----------------------

## Engineer
### **Team: Crewmates**
**The Engineer** là một vai trò trong nhóm Crewmate, với khả năng sửa chữa các sự cố và sử dụng các lối thông gió (vent) trong game. Vai trò này có những đặc điểm sau:

- **Sửa chữa sự cố từ xa:** Nếu Engineer còn sống, họ có thể sửa một số lượng sự cố nhất định trong game mà không cần phải ở gần nơi sự cố xảy ra. Điều này giúp họ hỗ trợ nhóm trong việc duy trì các hệ thống của tàu (hoặc môi trường trong game) mà không cần phải di chuyển đến từng khu vực bị hỏng.
- **Sử dụng lối thông gió:** Engineer có thể sử dụng các lối thông gió (vent), giống như Impostors. Điều này cho phép họ di chuyển nhanh chóng giữa các khu vực trên bản đồ mà không bị phát hiện. Tuy nhiên, khả năng này có thể tạo ra rủi ro nếu không sử dụng cẩn thận.
- **Cảnh báo cho nhóm Jackal/Impostor:** Nếu Engineer đang ở trong lối thông gió, tùy theo cài đặt, các thành viên trong nhóm Jackal hoặc Impostor có thể thấy một viền màu xanh xung quanh tất cả các lối thông gió trên bản đồ. Điều này giúp họ nhận biết sự hiện diện của Engineer trong các lối thông gió và có thể lập kế hoạch hành động.
  
**Lưu ý:**
- **Tính năng giết:** Nếu một Impostor đứng gần lối thông gió mà Engineer đang sử dụng, nút giết của Impostor sẽ được kích hoạt và Impostor có thể giết Engineer tại đó.
- **Không có ảnh hưởng từ hành động khác:** Các hành động như Morphling hay Shifter sẽ không thể ảnh hưởng đến các người chơi đang ở trong lối thông gió.
### Game Options
| Name | Description |
|----------|:-------------:|
| Engineer Spawn Chance | -
| Number Of Sabotage Fixes| -
| Impostors See Vents Highlighted | -
| Jackal And Sidekick See Vents Highlighted | -
-----------------------

## Sheriff
### **Team: Crewmates**
**The Sheriff** là một vai trò trong nhóm Crewmates với khả năng đặc biệt là có thể tiêu diệt các Impostors hoặc các vai trò Neutral (tùy theo cài đặt). Tuy nhiên, nếu họ cố gắng giết một Crewmate, họ sẽ tự chết.

**Lưu ý:**
- **Bắn vào người được bảo vệ bởi Medic:** Nếu Sheriff bắn vào người đã được Medic bảo vệ bằng khiên, cả Sheriff và người được bảo vệ sẽ **không bị thương**.
- **Bắn Mini Impostor:** Nếu Sheriff bắn một Mini Impostor trong khi chúng đang phát triển, không có gì xảy ra. Tuy nhiên, nếu Mini Impostor đã trưởng thành, nó sẽ bị giết.

### Game Options
| Name | Description |
|----------|:-------------:|
| Sheriff Spawn Chance | -
| Sheriff Cooldown | -
| Sheriff Can Kill Neutrals | -
| Sheriff Has A Deputy | Deputy can not be in game without Sheriff
-----------------------

## Deputy
### **Team: Crewmates**
**The Deputy** là một vai trò hỗ trợ trong nhóm Crewmates, với khả năng đặc biệt là có thể xích tay một người chơi khác. Khi bị xích tay, người chơi sẽ không thể sử dụng các chức năng quan trọng như kill, sử dụng các kỹ năng, vào vent, hoặc báo cáo thi thể.

**Lưu ý:**
- Thời gian bị xích bắt đầu sau khi còng tay trở nên hiển thị.
- Deputy không thể xuất hiện trong trò chơi nếu không có Sheriff.

### Game Options
| Name | Description |
|----------|:-------------:|
| Deputy Number Of Handcuffs | -
| Handcuff Cooldown| -
| Handcuff Duration | -
| Sheriff And Deputy Know Each Other | -
| Deputy Gets Promoted To Sheriff | "Off", "On (Immediately)" or "On (After Meeting)"
| Deputy Keeps Handcuffs When Promoted |-
-----------------------

## Lighter
### **Team: Crewmates**
**The Lighter** là một vai trò có tầm nhìn khác biệt so với các người chơi khác trong trò chơi, tùy thuộc vào cài đặt. Tầm nhìn của họ giống như hình chóp của đèn pin, có thể di chuyển quanh bản đồ (tương tự như chế độ Hide'n'Seek). 

**Lưu ý:**
- Tầm nhìn của Lighter có thể thay đổi theo các cài đặt và họ có thể điều chỉnh vị trí của vùng chiếu sáng trên bản đồ.

### Game Options
| Name | Description |
|----------|:-------------:|
| Lighter Spawn Chance | -
| Vision On Lights On | The vision the Lighter has when the lights are on
| Vision On Lights Off | The vision the Lighter has when the lights are down
| Flashlight Width | -
-----------------------

## Detective
### **Team: Crewmates**
**The Detective** có thể nhìn thấy dấu vết mà các người chơi khác để lại.\
Tính năng khác của Detective là khi họ báo cáo một xác chết, họ sẽ nhận được những manh mối về danh tính của kẻ giết người. Loại thông tin mà họ nhận được phụ thuộc vào thời gian mà họ tìm thấy xác chết.

**Lưu ý:**
- Khi người chơi thay đổi màu sắc (do Morph hoặc Camouflage), tất cả dấu vết cũng sẽ thay đổi màu (bao gồm cả những dấu vết đã có trên mặt đất). Khi các hiệu ứng hết tác dụng, tất cả dấu vết sẽ trở lại màu sắc ban đầu.
- Detective không thể thấy dấu vết của các người chơi đang ở trong ống thông gió (vents).
- Thêm thông tin về [màu sắc](#colors).

### Game Options
| Name | Description |
|----------|:-------------:|
| Detective Spawn Chance | -
| Anonymous Footprints | If set to true, all footprints will have the same color. Otherwise they will have the color of the respective player.
| Footprint Interval | The interval between two footprints
| Footprint Duration | Sets how long the footprints remain visible.
| Time Where Detective Reports Will Have Name | The amount of time that the Detective will have to report the body since death to get the killer's name.  |
| Time Where Detective Reports Will Have Color Type| The amount of time that the Detective will have to report the body since death to get the killer's color type. |
-----------------------

## Time Master
### **Team: Crewmates**
**The Time Master** có một lá chắn thời gian mà họ có thể kích hoạt. Lá chắn thời gian này sẽ duy trì hiệu lực trong một khoảng thời gian có thể cấu hình.\
Nếu một người chơi cố gắng giết Time Master khi lá chắn thời gian đang hoạt động, vụ giết sẽ không thành công và thời gian sẽ quay lại một khoảng thời gian đã định.

Thời gian hồi chiêu của kẻ giết người sẽ không được đặt lại, vì vậy Time Master phải đảm bảo rằng trò chơi sẽ không rơi vào tình huống tương tự.\
Time Master sẽ không bị ảnh hưởng bởi việc quay lại thời gian.

**Lưu ý:**
- Chỉ chuyển động của người chơi bị ảnh hưởng bởi việc quay lại thời gian.
- Cắn của Vampire sẽ kích hoạt việc quay lại thời gian. Nếu Time Master không kịp khiên cho cú cắn, họ vẫn có thể khiên cho cú giết xảy ra vài giây sau đó.
- Nếu Time Master bị cắn và có lá chắn khi cuộc họp được gọi, họ sẽ sống sót, nhưng thời gian sẽ không quay lại.
- Nếu Time Master có lá chắn của Medic, họ sẽ không bị quay lại.
- Lá chắn sẽ kết thúc ngay lập tức khi bị kích hoạt. Vì vậy, Time Master có thể bị tấn công ngay khi việc quay lại thời gian kết thúc.
### Game Options
| Name | Description |
|----------|:-------------:|
| Time Master Spawn Chance | - |
| Time Master Cooldown | - |
| Rewind Duration | How much time to rewind |
| Time Master Shield Duration |
-----------------------

## Medic
### **Team: Crewmates**
**The Medic** có thể tạo một lá chắn (được hiển thị bởi một viền xung quanh người chơi) cho một người chơi mỗi ván, làm cho người chơi đó không thể bị giết.\
Lá chắn cũng sẽ được hiển thị trong cuộc họp dưới dạng dấu ngoặc quanh tên của người chơi được bảo vệ.\
Người chơi được bảo vệ vẫn có thể bị bỏ phiếu ra ngoài và có thể là một Impostor.\
Nếu được thiết lập trong các tùy chọn, người chơi được bảo vệ và/hoặc Medic sẽ nhận một tia sáng đỏ trên màn hình nếu ai đó (Impostor, Sheriff, ...) cố gắng giết họ.\
Nếu Medic chết, lá chắn sẽ biến mất cùng với họ.\
Sheriff sẽ không chết nếu họ cố gắng giết một Crewmate được bảo vệ và sẽ không thực hiện vụ giết nếu họ cố gắng giết một Impostor được bảo vệ.\
Tùy thuộc vào các tùy chọn, các lần đoán từ Guesser sẽ bị chặn bởi lá chắn và người chơi/medic được bảo vệ có thể sẽ nhận thông báo.

Một tính năng khác của Medic là khi họ báo cáo một xác chết: họ sẽ thấy thời gian từ khi người chơi chết.

**Lưu ý:**
- Nếu người chơi được bảo vệ là một Lover và Lover còn lại chết, họ vẫn sẽ tự sát.
- Nếu Shifter có lá chắn hoặc mục tiêu của họ có lá chắn, người chơi được bảo vệ sẽ thay đổi.
- Lá chắn được đặt sau cuộc họp tiếp theo sẽ được đặt trước khi có thể thực hiện bất kỳ thay đổi nào do Shifter.

### Game Options
| Name | Description | Options |
|----------|:-------------:|:-------------:|
| Medic Spawn Chance | - | -
| Show Shielded Player | Sets who sees if a player has a shield | "Everyone", "Shielded + Medic", "Medic"
| Shielded Player Sees Murder Attempt| Whether a shielded player sees if someone tries to kill them | True/false |
| Shield Will Be Activated | Sets when the shield will be active | "Instantly", "Instantly, Visible After Meeting", "After Meeting"
| Medic Sees Murder Attempt On Shielded Player | If anyone tries to harm the shielded player (Impostor, Sheriff, Guesser, ...), the Medic will see a red flash | - |
-----------------------

## Swapper
### **Team: Crewmates**
**The Swapper** trong cuộc họp có thể hoán đổi số phiếu mà hai người chơi nhận được (tức là tất cả phiếu mà người chơi A nhận được sẽ được chuyển cho người chơi B và ngược lại).\
Vì sức mạnh của Swapper trong cuộc họp, họ không thể bắt đầu các cuộc họp khẩn cấp và không thể sửa đèn và liên lạc.\
Swapper hiện có một số lần hoán đổi ban đầu và có thể nạp lại các lần hoán đổi này sau khi hoàn thành một số lượng nhiệm vụ cấu hình được.

**Lưu ý:**
- Số lần hoán đổi còn lại sẽ được hiển thị trong dấu ngoặc bên cạnh vai trò của người chơi khi không ở trong cuộc họp.
- Trong cuộc họp, số lần hoán đổi sẽ xuất hiện bên cạnh nút "Xác nhận Hoán đổi".

### Game Options
| Name | Description
|----------|:-------------:|
| Swapper Spawn Chance | -
| Swapper Can Call Emergency Meeting | Option to disable the emergency button for the Swapper
| Swapper Can Only Swap Others | Sets whether the Swapper can swap themself or not
| Initial Swap Charges | -
| Number Of Tasks Needed For Recharging | -
-----------------------

## Seer
### **Team: Crewmates**
**The Seer** có hai khả năng (một trong số đó có thể được kích hoạt hoặc cả hai trong các tùy chọn).

1. **Khả năng 1:** Seer có thể nhìn thấy linh hồn của các người chơi đã chết trong vòng một vòng trước, các linh hồn này sẽ dần dần mờ đi.
   
2. **Khả năng 2:** Seer nhận được một ánh sáng màu xanh trên màn hình của họ nếu một người chơi chết ở đâu đó trên bản đồ.

**Lưu ý:** Các tính năng này có thể được cấu hình trong các tùy chọn game.

### Game Options
| Name | Description |
|----------|:-------------:|
| Seer Spawn Chance | -
| Seer Mode | Options: Show death flash and souls, show death flash, show souls
| Seer Limit Soul Duration | Toggle if souls should turn invisible after a while
| Seer Soul Duration | Sets how long it will take the souls to turn invisible after a meeting
-----------------------

## Hacker
### **Team: Crewmates**
**The Hacker** có thể kích hoạt chế độ "Hacker mode" để nhận được nhiều thông tin hơn so với những người chơi khác từ bảng admin và vitals trong một khoảng thời gian nhất định. Nếu không kích hoạt chế độ này, Hacker sẽ chỉ thấy thông tin như những người chơi khác.

**Thông tin từ Bảng Admin:** Hacker có thể thấy màu sắc (hoặc loại màu sắc) của các người chơi trên bảng admin.

**Thông tin từ Vitals:** Hacker có thể thấy thời gian người chơi đã chết bao lâu.

**Thiết bị di động:** Hacker có thể sử dụng các thiết bị di động (vitals và bảng admin) với số lần sử dụng tối đa và một số nhiệm vụ cấu hình sẵn cần hoàn thành để tái tạo lại năng lượng.

Khi đang sử dụng các thiết bị di động này, Hacker không thể di chuyển.

**Lưu ý:**
- Nếu Morphling biến hình hoặc Camouflager sử dụng khả năng ngụy trang, màu sắc trên bảng admin sẽ thay đổi tương ứng.
- Thêm thông tin về [màu sắc](#colors).

### Game Options
| Name | Description |
|----------|:-------------:|
| Hacker Spawn Chance | -
| Hacker Cooldown | -
| Hacker Duration | Sets how long the "Hacker mode" remains active
| Hacker Only Sees Color Type | Sets if the Hacker sees the player colors on the admin table or only white/gray (for Lighter and darker colors)
| Max Mobile Gadget Charges | -
| Number Of Tasks Needed For Recharging | Number of tasks to get a charge
| Can't Move During Cam Duration | -
-----------------------

## Tracker
### **Team: Crewmates**
**The Tracker** có thể chọn một người chơi để theo dõi. Tùy thuộc vào các thiết lập, Tracker có thể theo dõi một người chơi khác sau mỗi cuộc họp, hoặc theo dõi cùng một người chơi suốt trò chơi.

Một mũi tên sẽ chỉ ra vị trí theo dõi cuối cùng của người chơi. Mũi tên sẽ cập nhật vị trí của người đó sau một khoảng thời gian nhất định (có thể cấu hình).

Có thể thay thế hoặc kết hợp mũi tên với **Proximity Tracker** từ chế độ Hide N Seek, tùy thuộc vào các tùy chọn.

**Khả năng bổ sung:** Tùy theo cài đặt, Tracker có một khả năng khác: Họ có thể theo dõi tất cả các xác chết trên bản đồ trong một khoảng thời gian nhất định. Họ sẽ tiếp tục theo dõi xác chết, ngay cả khi chúng bị làm sạch hoặc bị ăn bởi Vulture.

**Lưu ý:**
- Nếu người chơi bị theo dõi ở một tầng khác trong chế độ **Submerged**, mũi tên sẽ luôn chỉ về thang máy.

### Game Options
| Name | Description
|----------|:-------------:|
| Tracker Spawn Chance | -
| Tracker Update Interval | Sets how often the position is being updated
| Tracker Reset Target After Meeting | -
| Tracker Can Track Corpses | -
| Corpses Tracking Cooldown | -
| Corpses Tracking Duration | -
| How Tracker Gets Target Location| -
-----------------------

## Snitch
### **Team: Crewmates**
**The Snitch** khi hoàn thành tất cả các nhiệm vụ của mình, sẽ nhận được thông tin trong chat về vị trí cuối cùng của tất cả các kẻ giết người khi cuộc họp bắt đầu.

Khi **Snitch** chỉ còn một số nhiệm vụ cấu hình được, sẽ có thông báo trên màn hình của các kẻ ác rằng có một Snitch trong trò chơi.

**Lưu ý:**
- Nếu Snitch chết, tất cả các kẻ giết người sẽ được thông báo về cái chết của Snitch.
- Vị trí cuối cùng có thể là một phòng hoặc một khu vực mở.

### Game Options
| Name | Description
|----------|:-------------:|
| Snitch Spawn Chance | -
| Task Count Where The Snitch Will Be Revealed | -
| Information Mode  | Whether the snitch will get info on the map and/or in the chat 
| Targets | Snitch Will See All Evil Players or Killing Evil Players
-----------------------

## Spy
### **Team: Crewmates**
**The Spy** là một Crewmate không có khả năng đặc biệt.

**The Spy** trông giống như một Impostor bổ sung đối với các Impostor, và họ không thể phân biệt được.

Có hai khả năng (tùy thuộc vào các tùy chọn thiết lập):
- Các Impostor không thể giết Spy (bởi vì nếu không, nút giết của họ sẽ tiết lộ ai là Spy).
- Các Impostor có thể giết Spy nhưng họ cũng có thể giết đối tác Impostor của mình (nếu họ nhầm một Impostor khác với Spy).

Bạn có thể thiết lập xem Sheriff có thể giết Spy hay không (để giữ bí mật về Spy).

**Lưu ý:**
- Nếu Spy bị sidekicked, họ vẫn sẽ xuất hiện màu đỏ với các Impostor.

### Game Options
| Name | Description
|----------|:-------------:|
| Spy Spawn Chance |
| Spy Can Die To Sheriff |
| Impostors Can Kill Anyone If There Is A Spy | This allows the Impostors to kill both the Spy and their Impostor partners
| Spy Can Enter Vents | Allow the Spy to enter/exit vents (but not actually move to connected vents)
| Spy Has Impostor Vision | Give the Spy the same vision as the Impostors have
-----------------------

## Portalmaker
### **Team: Crewmates**
**The Portalmaker** là một Crewmate có thể đặt hai cổng (portals) trên bản đồ.

Hai cổng này được kết nối với nhau. Sau cuộc họp tiếp theo, những cổng này sẽ hiển thị và có thể được sử dụng bởi tất cả người chơi.

Ngoài ra, **The Portalmaker** sẽ nhận được thông tin về ai đã sử dụng các cổng và khi nào trong chat của mỗi cuộc họp, tùy theo các thiết lập.

Nếu cài đặt được bật, **The Portalmaker** có thể dịch chuyển bản thân đến các cổng đã đặt từ bất kỳ đâu.

**Lưu ý:**
- Nút sử dụng cổng sẽ xuất hiện sau khi **The Portalmaker** đặt cổng và một cuộc họp hoặc báo cáo thi thể được gọi.
- Khi một người chơi sử dụng cổng, cổng sẽ bị khóa đối với người chơi khác cho đến khi người chơi đó đã được dịch chuyển.
- Các hồn ma vẫn có thể sử dụng cổng, nhưng sẽ không làm cản trở bất kỳ người sống nào sử dụng nó, và **The Portalmaker** sẽ không nhận được thông tin về điều này trong chat.
- Nếu một người biến hình sử dụng cổng, tên/màu của người biến hình sẽ hiển thị tùy theo các thiết lập.
- Nếu một người ngụy trang sử dụng cổng, sẽ hiển thị "A camouflaged person used the portal."

### Game Options
| Name | Description
|----------|:-------------:|
| Portalmaker Spawn Chance | -
| Portalmaker Cooldown | -
| Use Portal Cooldown | -
| Portalmaker Log Only Shows Color Type | -
| Log Shows Time | -
| Can Port To Portal From Everywhere | -
-----------------------

## Security Guard
### **Team: Crewmates**
**The Security Guard** là một Crewmate có số lượng vít nhất định mà họ có thể sử dụng để niêm phong các cổng thông gió (vents) hoặc đặt các camera mới.

Mỗi lần đặt camera mới và niêm phong cổng thông gió sẽ tốn một số vít cấu hình sẵn. Tổng số vít mà **The Security Guard** có thể có cũng có thể được cấu hình.

Camera mới sẽ hiển thị sau cuộc họp tiếp theo và có thể được sử dụng bởi tất cả người chơi. Cổng thông gió sẽ bị niêm phong sau cuộc họp tiếp theo, người chơi không thể vào hoặc ra từ những cổng này, nhưng họ vẫn có thể "di chuyển đến chúng" dưới lòng đất.

**Lưu ý:**
- Các hộp Trickster không thể bị niêm phong.
- **The Security Guard** không thể đặt camera trên MiraHQ.
- Số vít còn lại sẽ được hiển thị phía trên nút đặc biệt của họ.
- Trên Skeld, bốn camera sẽ được thay thế mỗi 3 giây (với bốn camera tiếp theo). Người chơi cũng có thể di chuyển thủ công bằng cách sử dụng phím mũi tên.
- **The Security Guard** có thể truy cập camera di động sau khi đã đặt hết tất cả vít.
- Trong khi truy cập các camera di động, **The Security Guard** không thể di chuyển.
### Game Options
| Name | Description
|----------|:-------------:|
| Security Guard Spawn Chance |
| Security Guard Cooldown |
| Security Guard Number Of Screws | The number of screws that a Security Guard can use in a game
| Number Of Screws Per Cam | The number of screws it takes to place a camera
| Number Of Screws Per Vent | The number of screws it takes to seal a vent
| Security Guard Duration | -
| Gadget Max Charges | -
| Number Of Tasks Needed For Recharging | -
| Can't Move During Cam Duration | -
-----------------------

## Medium
### **Team: Crewmates**
**The Medium** là một Crewmate có khả năng hỏi hồn của các người chơi đã chết để lấy thông tin. Tương tự như **The Seer**, Medium sẽ thấy hồn của các người chơi đã chết (sau cuộc họp tiếp theo) và có thể đặt câu hỏi với họ. Sau khi hỏi, Medium sẽ nhận được thông tin ngẫu nhiên về linh hồn hoặc kẻ giết người trong trò chơi qua chat. Những hồn này chỉ tồn tại trong một vòng, tức là cho đến cuộc họp tiếp theo. Tùy vào các tùy chọn, các linh hồn có thể chỉ được hỏi một lần rồi biến mất.

### Các câu hỏi:

- Các linh hồn sẽ luôn ưu tiên trả lời với thông tin liên quan đến vai trò của họ trước!

### Thông tin đặc biệt theo vai trò:
- **Sheriff tự sát**: "Yikes, that Sheriff shot backfired."
- **Thief tự sát**: "I tried to steal the gun from their pocket, but they were just happy to see me."
- **Lover (hoạt động) chết**: "I wanted to get out of this toxic relationship anyways."
- **Lover (thụ động) tự sát**: "The love of my life died, thus with a kiss I die."
- **Lawyer bị giết bởi khách hàng**: "My client killed me. Do I still get paid?"
- **Jackal/Sidekick giết đồng đội**: "First they sidekicked me, then they killed me... BUT WHY?"
- **Impostor giết đồng đội**: "I guess they confused me for the Spy, is there even one?"
- **O2-kill trên Submerged**: "Do I really need that mask for breathing?"
- **Warlock tự giết**: "MAYBE I cursed the person next to me and killed myself. Oops."
- **Vulture/Cleaner ăn/lau xác chết**: "Is my dead body some kind of art now or... aaand it's gone."

### Thông tin ngẫu nhiên:
- "I'm not sure, but I guess a darker/lighter color killed me."
- "If I counted correctly, then I died x seconds before the meeting started."
- "If my role hasn't been saved, there's no (role) in the game anymore."
- "It seems like my killer was the (role)."

### Xác suất câu trả lời có thông tin bổ sung:
- Khi bạn hỏi, x kẻ giết vẫn còn sống.
- Khi bạn hỏi, x người chơi có thể sử dụng cổng thông gió (vent) vẫn còn sống.
- Khi bạn hỏi, x người chơi là trung lập nhưng không thể giết vẫn còn sống.

### Game Options
| Name | Description
|----------|:-------------:|
| Medium Spawn Chance | -
| Medium Cooldown | -
| Medium Duration | The time it takes to question a soul
| Medium Each Soul Can Only Be Questioned Once | If set to true, souls can only be questioned once and then disappear
| Chance That The Answer Contains The Remaining Amount Of Killing Roles | Chance includes Sheriff and Thief
-----------------------

## Trapper
### **Team: Crewmates**

**The Trapper** là một Crewmate có khả năng đặt bẫy để gài bẫy người chơi và thu thập thông tin từ họ.  
Các bẫy sẽ làm người chơi mắc kẹt trong một khoảng thời gian x giây (tùy theo cài đặt) và tiết lộ thông tin qua chat về "Vai trò" của họ, liệu họ là "Vai trò Tốt/Xấu", hoặc "Tên" của họ.  
Bẫy sẽ không hiển thị cho đến khi một số lượng người chơi nhất định bị gài bẫy (có thể cấu hình).  
Khi bẫy hiển thị, Trapper sẽ nhận thông tin qua chat (theo thứ tự ngẫu nhiên).  
Nếu một bẫy bị kích hoạt (và tùy chọn này được bật), bản đồ của Trapper sẽ mở ra và chỉ ra bẫy nào đã bị kích hoạt.  
Các bẫy có một số lần sử dụng tối đa (số lần sử dụng) và một lượng nhiệm vụ cấu hình sẵn cần hoàn thành để nạp lại.

### **LƯU Ý:**
- Trapper không thể bị gài bẫy trong chính bẫy của mình.



### Game Options
| Name | Description
|----------|:-------------:|
| Trapper Spawn Chance | -
| Trapper Cooldown | -
| Max Traps Charges | -
| Number Of Tasks Needed For Recharging | -
| Trap Needed Trigger To Reveal | -
| Show Anonymous Map | -
| Trap Information Type | "Name", "Role", "Good/Evil Role"
| Trap Duration | -
-----------------------

# Modifier
**Modifier: Bloody**

Nếu bị giết, **Bloody Modifier** sẽ để lại một dấu vết cho x giây trên người kẻ giết họ. Dấu vết này sẽ có màu sắc của người bị giết.

**LƯU Ý:**
- Các vai trò Impostor, Neutral hoặc Crewmate có thể có Modifier này.
### Game Options
| Name | Description |
|----------|:-------------:|
| Bloody Spawn Chance | -
| Bloody Quantity | -
| Trail Duration | -
-----------------------

## Anti Teleport

**Modifier: Anti Teleport**

**Anti Teleport Modifier** ngăn không cho người chơi bị dịch chuyển đến Bàn Họp nếu một xác chết được báo cáo hoặc cuộc Họp Khẩn Cấp được gọi.\
Người chơi sẽ bắt đầu vòng chơi tại vị trí kết thúc của vòng trước (Kêu gọi Họp Khẩn Cấp/Báo cáo Xác Chết).

**LƯU Ý:**
- Các vai trò Impostor, Neutral hoặc Crewmate có thể có Modifier này.

### Game Options
| Name | Description |
|----------|:-------------:|
| Anti Teleport Spawn Chance | -
| Anti Teleport Quantity | -
-----------------------

## Tie Breaker

**Modifier: Tie Breaker**

Nếu cuộc Bỏ Phiếu kết thúc với tỉ số hòa, **Tie Breaker** sẽ được áp dụng và người chơi có **Tie Breaker Modifier** sẽ có thêm một phiếu bầu không hiển thị cho bất kỳ ai.\
Mọi người sẽ biết liệu **Tie Breaker** có được áp dụng trong cuộc Họp hay không.

**LƯU Ý:**
- Các vai trò Impostor, Neutral hoặc Crewmate có thể có Modifier này.
- Chỉ có thể có một người chơi sở hữu Modifier này.

### Game Options
| Name | Description |
|----------|:-------------:|
| Tie Breaker Spawn Chance | -
-----------------------

## Bait

**Modifier: Bait**

**Bait** buộc kẻ giết người phải tự báo cáo thi thể (bạn có thể cấu hình độ trễ trong các tùy chọn).\
Có thể có nhiều hơn một **Bait**.

**LƯU Ý:**
- Nếu Sheriff có **Bait Modifier** và chết khi cố gắng giết Crewmate, Sheriff sẽ *KHÔNG* tự báo cáo.
- Các vai trò Impostor, Neutral hoặc Crewmate có thể có Modifier này.

### Game Options
| Name | Description
|----------|:-------------:|
| Bait Spawn Chance | -
| Bait Quantity | -
| Bait Report Delay Min | -
| Bait Report Delay Max | -
| Warn The Killer With A Flash | -
-----------------------

## Lovers

**Lovers**

Luôn có hai Lovers liên kết với nhau.\
Mục tiêu chính của họ là sống sót cùng nhau cho đến cuối trò chơi.\
Nếu một Lover chết (và tùy chọn được kích hoạt), Lover còn lại sẽ tự sát.\
Bạn có thể xác định tỷ lệ của một Lover là Impostor.\
Lovers không bao giờ biết vai trò của đối tác của họ, họ chỉ biết ai là đối tác của mình.\
Lovers thắng nếu cả hai còn sống khi trò chơi kết thúc. Họ cũng có thể thắng với đội ban đầu của mình (ví dụ, một Lover là Impostor có thể thắng cùng Impostors, một Lover là Arsonist vẫn có thể đạt được chiến thắng Arsonist).\
Nếu một trong các Lovers là kẻ giết người (ví dụ: Jackal/Sidekick/Impostor), họ có thể đạt được chiến thắng "Lovers solo win" mà chỉ Lovers thắng.\
Nếu không có kẻ giết người nào trong Lovers (ví dụ: Lover là Arsonist + Lover là Crewmate) và cả hai còn sống khi trò chơi kết thúc, họ sẽ thắng cùng Crewmates.\
Nếu có Impostor/Jackal + Lover là Crewmate trong trò chơi, các nhiệm vụ của Lover là Crewmate sẽ không được tính (để đạt chiến thắng nhiệm vụ) trong khi họ còn sống.\
Nếu Lover chết, các nhiệm vụ của họ sẽ được tính.\
Bạn có thể bật một cuộc trò chuyện chỉ dành cho Lovers.

**LƯU Ý:**
Trong trường hợp 2 Crewmates vs 2 Impostors (hoặc 2 thành viên của đội Jackal) và Lovers không cùng đội, trò chơi sẽ không tự động kết thúc vì Lovers vẫn có thể đạt chiến thắng solo. Ví dụ: nếu còn các vai trò như Impostor + ImpLover + Lover + Crewmate, trò chơi sẽ không kết thúc và cú giết tiếp theo sẽ quyết định đội nào thắng: Impostors hay Lovers.

### Game Options
| Name | Description |
|----------|:-------------:|
| Lovers Spawn Chance | -
| Chance That One Lover Is Impostor | -
| Both Lovers Die | Whether the second Lover suicides, if the first one dies
| Enable Lover Chat | -
-----------------------

**NOTE:**
- As in a kill, if your Lover gets guessed, you will die with them.

## Sunglasses

**Sunglasses**

Sunglasses sẽ làm giảm tầm nhìn của Crewmates một tỷ lệ nhỏ. Tỷ lệ phần trăm này có thể cấu hình trong các tùy chọn.\
Tầm nhìn cũng sẽ bị ảnh hưởng khi tắt đèn.

**LƯU Ý:**
- Sunglasses chỉ ảnh hưởng đến Crewmates.
- Nếu bạn có Modifier Sunglasses và bị sidekicked, bạn sẽ mất Modifier này.

### Game Options
| Name | Description
|----------|:-------------:|
| Sunglasses Spawn Chance | -
| Sunglasses Quantity | -
| Vision With Sunglasses | -
-----------------------

## Mini

**Mini**

Nhân vật của Mini nhỏ hơn và do đó dễ thấy đối với mọi người trong trò chơi.\
Mini không thể bị giết cho đến khi nó tròn 18 tuổi, tuy nhiên nó có thể bị bỏ phiếu loại.

**Impostor/Jackal Mini:**
- Trong khi phát triển, thời gian làm mới kill của Mini sẽ bị gấp đôi. Khi nó trưởng thành hoàn toàn, thời gian làm mới kill chỉ còn 2/3 so với mặc định.
- Nếu bị ném ra khỏi tàu, mọi chuyện vẫn ổn.

**Crewmate Mini:**
- Mini Crewmate muốn tận dụng sự bất khả xâm phạm của nó trong giai đoạn đầu game.
- Nếu Mini bị ném ra khỏi tàu trước khi tròn 18 tuổi, mọi người sẽ thua. Hãy suy nghĩ kỹ trước khi bỏ phiếu loại Mini.

**Neutral Mini:**
- Thời gian làm mới không bị ảnh hưởng, ngoại trừ khi là Team Jackal/Sidekick.
- Nếu Mini bị ném ra khỏi tàu, mọi chuyện vẫn ổn ngoại trừ Jester.
- Nếu Mini là Jester bị bỏ phiếu loại, game sẽ kết thúc với chiến thắng của Jester.

**LƯU Ý:**
- Nếu Sheriff cố giết Mini trước khi nó trưởng thành hoàn toàn, không có gì xảy ra.
- Sheriff có thể giết Mini Impostor/Neutral, nhưng chỉ khi nó đã trưởng thành hoàn toàn.
- Nếu vai trò chính của Mini bị đoán đúng, nó sẽ chết như mọi vai trò khác và không có gì xảy ra thêm.

### Game Options
| Name | Description |
|----------|:-------------:|
| Mini Spawn Chance | -
| Mini  | Mini Growing Up Duration
| Mini Grows Up In Meeting | -
-----------------------

## VIP

**VIP (Very Important Player) Modifier**

Một Impostor, Jackal hoặc Crewmate có thể bị ảnh hưởng bởi Modifier VIP (Người chơi Quan trọng).\
VIP sẽ hiển thị cho tất cả mọi người khi anh ta chết với một tia sáng giống như Tia sáng của Seer.\
Nếu tùy chọn "Hiển thị Màu Đội" được bật, tất cả mọi người sẽ thấy tia sáng màu sắc của đội mà người chơi thuộc về.

**Các đội:**
- Impostor = Đỏ
- Neutral = Xanh dương
- Crewmate = Trắng
### Game Options
| Name | Description
|----------|:-------------:|
| VIP Spawn Chance | -
| VIP Quantity | -
| Show Team Color | -
-----------------------

## Invert

**Invert Modifier**

Modifier Invert sẽ đảo ngược các điều khiển của bạn (dù là bàn phím hay chuột).

**LƯU Ý**
- Các vai trò Impostor, Neutral hoặc Crewmate có thể có Modifier này.

### Game Options
| Name | Description
|----------|:-------------:|
| Invert Spawn Chance | -
| Invert Quantity | -
-----------------------

## Chameleon

**Chameleon Modifier**

Chameleon trở nên (một phần hoặc hoàn toàn) vô hình khi đứng yên trong x giây (tùy thuộc vào cài đặt).

**LƯU Ý**
- Bạn có thể sử dụng khả năng trong khi vô hình, chỉ khi di chuyển bạn mới trở lại rõ ràng.
- Các vai trò Impostor, Neutral hoặc Crewmate có thể có Modifier này.

### Game Options
| Name | Description
|----------|:-------------:|
| Chameleon Spawn Chance | -
| Chameleon Quantity | -
| Time Until Fading Starts | -
| Fade Duration | - 
| Minimum Visibility | -
-----------------------

## Shifter

**Shifter Modifier**

Shifter là một Modifier cho phép người chơi chuyển vai trò với một người chơi khác. Nếu người chơi kia là Crewmate, họ sẽ hoán đổi vai trò với nhau.\
Việc hoán đổi vai trò với Impostor hoặc Neutral sẽ thất bại và Shifter sẽ tự tử sau cuộc họp tiếp theo (sẽ không có xác chết).

Việc chuyển vai trò sẽ luôn được thực hiện vào cuối cuộc họp tiếp theo ngay trước khi một người chơi bị trục xuất. Mục tiêu cần được chọn trong suốt vòng chơi.\
Ngay cả khi Shifter hoặc mục tiêu chết trước cuộc họp, việc chuyển vai trò vẫn sẽ được thực hiện.

**LƯU Ý:**
- Việc chuyển vai trò của Shifter luôn được kích hoạt trước khi Erase (do đó, vai trò mới của Shifter sẽ bị xóa hoặc Shifter sẽ nhận vai trò của mục tiêu, tùy thuộc vào người Eraser đã xóa ai).
- Các khả năng sử dụng một lần (ví dụ: bảo vệ người chơi hoặc sửa chữa phá hoại của Engineer) chỉ có thể được sử dụng bởi một người chơi trong game (tức là Shifter chỉ có thể sử dụng chúng nếu người chơi trước đó chưa sử dụng).
- Nút Shifter nằm ở góc dưới bên trái, ngay cạnh nút tỏi (nếu Vampire được kích hoạt).
- Chỉ có vai trò Crewmate mới có thể có Modifier này.

### Game Options
| Name | Description
|----------|:-------------:|
| Shifter Spawn Chance | -
-----------------------

## Armored

**Armored Modifier**

Armored là một Modifier bảo vệ người chơi khỏi phát bắn đầu tiên có thể giết họ. Mỗi vòng chơi chỉ có một người chơi được áp dụng Armored.

**LƯU Ý:**
- Armored chỉ có hiệu lực trong vòng chơi và không bảo vệ khỏi việc đoán vai trò hoặc bị bỏ phiếu.
- Armored được áp dụng sau tất cả các lá chắn hoặc bảo vệ khác, vì vậy Armor chỉ vỡ nếu người chơi lẽ ra đã chết.
- Nếu một kẻ giết người cố gắng giết Armored, chúng sẽ thấy Armor vỡ với một hoạt hình đẹp mắt.
- Người chơi Armored sẽ không có bất kỳ chỉ báo nào cho biết Armor còn hoạt động hay không, trừ khi họ phá vỡ nó (Warlock, Sheriff, Thief).
### Game Options
| Name | Description
|----------|:-------------:|
| Armored Spawn Chance | -
-----------------------

# Gamemodes
Gamemodes can be switched when creating a lobby or inside the lobby by using a command in the chat:
`/gm <gamemode>`. Use the following gamemodes: `guess` or `gm`,`prophunt` or `ph`, `hidenseek` or `hns`. If `/gm` is used without argument or the argument can't be parsed, the lobby will switch to classic mode.


## Guesser Modifier
The **Guesser-Gamemode** is an extension to the Classic-Gamemode and gives you a multitude of new options for Guessers.\
The Guesser is now like an addition and can be applied to all players IF you want to. Settings are available to set the number of guessers for each team separately (Impostor, Neutral, Crewmate).\
When playing this game mode, the Guessers can have another role (e.g. Medic Guesser). The same
applies of course for Impostor and/or Neutral roles.\
Players can additionally have a modifier, if enabled (e.g. Medic Guesser Mini).

### Game Options
| Name | Description
|----------|:-------------:|
| Number of Crew Guessers | -
| Number of Neutral Guessers | -
| Number of Impostor Guessers | -
| Force Jackal Guesser | If set to "On", the first neutral role who will be Guesser is the Jackal. 
| Sidekick Is Always Guesser | The converted sidekick will become a guesser | -
| Force Thief Guesser | If set to "On", the first (or second if Force Jackal Guesser) neutral role who will be Guesser is the Thief.
| Guessers Can Have A Modifier | -
| Guesser Number Of Shots | -
| Guesser Can Shoot Multiple Times Per Meeting | -
| Number Of Tasks Needed To Unlock Shooting For Crew Guesser | - 
| Guesses Ignore The Medic Shield | -
| Evil Guesser Can Guess The Spy | -
| Guesser Can't Guess Snitch When Tasks Completed | -
-----------------------

**NOTE**
- If a Crewmate Guesser gets sidekicked, they will remain a Guesser even if the host (maybe) has set up only 1 "Neutral role Guesser".

## Hide 'n Seek
The **Hide 'n Seek-Gamemode** is a standalone Gamemode where Hunter have to catch their prey ("Hunted" players).\
The Hunter and Hunted player who are still alive are displayed to everyone in the bottom left corner (similar to the Arsonist display).\
When the game starts, the Hunter's movement is disabled for x-seconds (depends on the settings).\
There is a time-limit for each round, if the timer runs out and at least one Hunted is still alive, the Crew wins. The Hunted players can also win, if Taskwin is enabled and the Crew completes all tasks.\
If the Hunters kill all players before one of these conditions is triggered, the Hunters win.\

#### Hunter Abilities:
- Enable arrows (arrows point to all Hunted players for x-seconds (depending on settings))
- Mobile Admin table (like Hacker)
- Lighter ability (gives the Hunter a biggier vision radius for x-seconds (depending on settings))

#### Hunted Ability:
- Timeshield (like Timemaster, depending on settings)

Each Hunter action or finished Crew task will lower the timer by a configurable amount of time.\
\
**NOTE:**
- We added a vent on Polus (Specimen), but only for this Gamemode. The vent is connected with Admin & Lab.
- The Report button lights up, but cannot be pressed.
- The tasks can be configured separately for this mode, without affecting your normal game settings.
- Only the Hunter will be rewinded if they try to kill a player with an active timeshield.

### Game Options
| General | Description | Hunter | Description | Hunted | Description |
|----------|:-------------:|----------|:-------------:|----------|:-------------:|
| Map | -                                | Hunter Light Cooldown | -                  | Hunted Shield Cooldown | -
| Number Of Hunters | -                  | Hunter Light Duration | -                  | Hunted Shield Duration | -
| Kill Cooldown | -                      | Hunter Light Vision | -                    | Hunted Rewind Time | -
| Hunter Vision | -                      | Hunter Light Punish in Sec | -             | Hunted Shield Number | -
| Hunted Vision | -                      | Hunter Admin Cooldown | -
|  | -                       | Hunter Admin Duration | -
|  | -                        | Hunter Admin Punish In Sec | -
|  | -                         | Hunter Arrow Cooldown | -
|  | -                       | Hunter Arrow Duration | -
| Task Win Is Possible | -               | Hunter Arrow Punish In Sec | -
| Finish Tasks Punish In Sec | -
| Enable Sabotages | -
| Time The Hunter Needs To Wait | -

## PropHunt
The **Prop-Gamemode** is a standalone Gamemode where Hunters have to find the disguised players ("Props").\
The Hunters and Props who are still alive are displayed to everyone in the bottom left corner (similar to the Arsonist display).\
When the game starts, the Hunter's movement is disabled for x-seconds (depends on the settings), and their screen is blacked out.\
There is a time-limit for each round, if the timer runs out and at least one Prop is still alive, the remaining Props win.\
If the Hunters kill all players before the timer runs out the Hunters win.\
When a Prop dies, they will either join the Hunter team or die (setting).

#### Shared Abilities:
- Unstuck: By pressing this button, you can travel through walls for a short time. This is needed, because props sometimes get stuck in walls, due to their changed colliders. Don't use it to cheat!

#### Hunter Abilities:
- Reveal: A random players current prop is revealed to all players for x seconds (according to settings). The timer will be reduced by *punish* s.
- Mobile Admin table (like Hacker) - Normal Admin table shares the cooldown
- Find: Display the DangerMeter known from Vanilla HideNSeek for x seconds. The dangerlevel is rising the closer the Hunter gets to the neares prop.  
#### Prop Abilities:
- Invisibility: As a disguised Prop, become invisible for x seconds.
- Speedboost: Move faster for x seconds.
- Disguise: While near a usable object, press the button to disguise as the displayed object!

**NOTE:**
- The Report button lights up, but cannot be pressed.
- Hunters can vent
- The Kill Button and Vent Button are permanently enabled, so that you cannot use them to check if there is a prop nearby
- The Kill Button can always be pressed, but you can also miss if no Prop is nearby. The cooldown can be configured for hits and misses seperately.
- Usable prop objects are: All task consoles as well as many objects (rocks, snowpeople, barriers, beds, tables, ...)
- Any object on **LevelImposter** maps, that contains `liprop` in its name and has a `SpriteRenderer` (+ Sprite) will be usable as a prop too!


### Game Options
| General | Description | Hunter | Description | Hunted | Description |
|----------|:-------------:|----------|:-------------:|----------|:-------------:|
| Map | -                     | Number of Hunters | -                  | Props Become Hunters When Found | -
| Timer in Min | -            | Initial Blackout Duration | -          | Invisibility Enabled | -
| Unstuck Cooldown | -        | Kill Cooldown After Miss | -           | Invisibility Cooldown | -
| Unstuck Duration | -        | Kill Cooldown After Hit | -            | Invisibility Duration | -
| Hunter Vision | -           | Reveal Prop Cooldown | -               | Speedboost Enabled | -
| Prop Vision | -             | Reveal Prop Duration | -               | Speedboost Cooldown | -
|  | -             | Reveal Time Punish | Deducted from rem. timer | Speedboost Duration | - 
|  | -                         |  Hunter Admin Cooldown | - | Speedboost Ratio | Factor with which speed is multiplied 
|  | -                       | Find Cooldown | -
|  | -               | Find Duration | -

## GCERROR
If the error message "Fatal Error in GC - Collecting from unknown thread" stops you from playing the game, you can now disable the mod-updater, which causes this error.
In order to do this, create a file called `noupdater.txt` in your modded Among Us folder.

# License
TheOtherRolesAU/TheOtherRoles is licensed under the

[GNU General Public License v3.0](https://github.com/TheOtherRolesAU/TheOtherRoles/blob/main/LICENSE)

Permissions of this strong copyleft license are conditioned on making available **complete source code of licensed works and modifications**, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

# Bugs, suggestions and requests
If you found any bugs, have an idea for a new role or any other request, join our [Discord server](https://discord.gg/77RkMJHWsM).

# Copyedit
Thanks for fixing our typos [jacktose](https://github.com/jacktose) ✌️
