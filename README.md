# GusetHouse
GuestHouse management application 

# how to use...
- First import the database in the backup folder.
- Enter the database address in the form1 file(line : 21,22)

Note : Database features written in Persian

# database Tables 
account
- نام : name
- نام‌خانوادگی : Family name
- کدملی : id(number) --> key
- رمز : password
- تگ : tag
- حقوق : salary


add_delete_person
- فاعل : sturdy
- مفعول : done
- عمل : action
- زمان انجام : Time to do


Backup_Restore
- کاربر : user
- عمل : action
- زمان انجام : Time to do


change_person_info
- فاعل : sturdy
- مفعول : done
- زمان انجام : Time to do


delivery_payment
- نام مهمان : guest name
- شناسه اتاق : room id
- هزینه کل : overall cost 
- زمان پرداخت : pay time


guest_info
- نام : name
- نام خانوادگی : family name
- کد ملی : id


Login/out
- کاربر : user
- ورود/خروج : in/out
- زمان انجام : Time to do


payment
- نام مدیر : manager name
- شناسه مدیر : manager id
- حقوق : salary
- تاریخ : date


reserve
- کد ملی مهمان : guest id
- شناسه اتاق : room id
- زمان ورود : Arrival time
- زمان خروج : Exit time


room_info
- شناسه اتاق : room id
- ظرفیت اتاق : room capacity
- هزینه اتاق : room cost
- وضعیت اتاق : room status 

language programming : C#
lang : fa(Persian)
