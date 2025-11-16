local VirtualUser = game:GetService('VirtualUser')
 
game:GetService('Players').LocalPlayer.Idled:Connect(function()
    VirtualUser:CaptureController()
    VirtualUser:ClickButton2(Vector2.new())
end)
 
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "Anti AFK loaded!",
    Text = "Made by d1_ofc",
    Button1 = "Moon HUB On Top",
    Duration = 5
})
