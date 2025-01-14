local VirtualUser = game:GetService('VirtualUser')
 
game:GetService('Players').LocalPlayer.Idled:Connect(function()
    VirtualUser:CaptureController()
    VirtualUser:ClickButton2(Vector2.new())
end)
 
game:GetService("StarterGui"):SetCore("SendNotification", {
    Title = "MoonHUB AntiAFK loaded!",
    Text = "Made by lk_.12",
    Button1 = "Ok",
    Duration = 5
})
