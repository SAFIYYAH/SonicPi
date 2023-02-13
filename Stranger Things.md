# SonicPi
use_bpm 160
use_synth :blade

live_loop :sound do
  sample :bass_thick_c
  sleep 2
end

live_loop :sound do
  #sample :bass_drop_c, amp: 1
  play:c4
  sleep 0.5
  play :e4
  sleep 0.5
  play :g4
  sleep 0.5
  play :b4
  sleep 0.5
  play :c5
  sleep 0.5
  play :b4
  sleep 0.5
  play :g4
  sleep 0.5
  play :e4
  sleep 0.5
end
