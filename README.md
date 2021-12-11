for i, a in pairs(getgc(true)) do
 if type(a) == 'table' and rawget(a, "aimrotkickmin") then
   a.aimrotkickmin = Vector3.new(0,0,0)
   a.aimrotkickmax = Vector3.new(0,0,0)
   a.aimtranskickmin = Vector3.new(0,0,0)
   a.aimtranskickmax = Vector3.new(0,0,0)
   a.aimcamkickmin = Vector3.new(0,0,0)
   a.aimcamkickmax = Vector3.new(0,0,0)
   a.rotkickmin = Vector3.new(0,0,0)
   a.rotkickmax = Vector3.new(0,0,0)
   a.transkickmin = Vector3.new(0,0,0)
   a.transkickmax = Vector3.new(0,0,0)
   a.camkickmin = Vector3.new(0,0,0)
   a.camkickmax = Vector3.new(0,0,0)
   a.aimcamkickspeed = 99999
   a.modelkickspeed = 9999
   a.modelrecoverspeed = 9999
   a.firerate = 1000 --Change to your own
 end
end
