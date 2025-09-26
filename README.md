# RayCasting2
       RayCasting2 by @Astrally0
	   
       -----------------------------[English translation]-------------------------------------
       What is RayCasting2?
       RayCasting2 is a module that allows you to create a raycast. 
       You can also use functions using a constructor.
       
       ------------------------------------------------------------------
       Constructor Documentation:
       The constructor can be used for different actions
       
       For example:
       
       change the color of an object when it is hit by a raycast,
       change the transparency of an object when it is hit by a raycast,
       destroy an object when it is hit by a raycast,
       and much more.
       
       ------------------------------------------------------------------
       How to use constructor?
       
       also if you add to the constructor: 1) RemoteEvent, 2) RemoteFunction, 3) UnreliableRemoteEvent, 4) Script, 5) Model, 6) Part
       EXAMPLE SCRIPT:
-----------------------------[1 Anchored]-----------------------------------
local Constructor_Anchored = {}

function Constructor_Anchored:Init(Arg1: RaycastResult)
        if not Arg1 then return end

	if Arg1 then
		Arg1.Instance.Anchored = true -- change to your size
	end
end

return Constructor_Anchored

--------------------------------------------------------------------

-----------------------------[2 Color3]-----------------------------------

local Constructor_Color3 = {}

function Constructor_Color3:Init(Arg1: RaycastResult)
	if not Arg1 then return end

	if Arg1 then
		Arg1.Instance.Color = Color3.new(1, 0, 0) -- change to your color
	end
end

return Constructor_Color3

        -----------------------------[Русский перевод]-------------------------------------     
       Что такое RayCasting2?
       RayCasting2 — это модуль, позволяющий создавать лучи.
       Вы также можете использовать функции с помощью конструктора.
              
       ------------------------------------------------------------------
       Документация конструктора:
       Конструктор можно использовать для различных действий,

       Например:

       изменение цвета объекта при попадании в него лучом луча,
       изменение прозрачности объекта при попадании в него лучом луча,
       уничтожение объекта при попадании в него лучом луча,
       и многое другое.
              
       ------------------------------------------------------------------
       Как использовать конструктор?

       Также, если добавить в конструктор: 1) RemoteEvent, 2) RemoteFunction, 3) UnreliableRemoteEvent, 4) Script, 5) Model, 6) Part

	   
