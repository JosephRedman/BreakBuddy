# BreakBuddy!
<tiny>A transparent, always-on-top desktop pet that keeps you company and monitors your workplace health.</tiny>

## Quality of life improvements:
- Ambient stress alerts: Monitors your heart rate from your Huawei watch. When your heart rate spikes above baseline, BreakBuddy displays a calming state, and offers tips for you to get back to your calm routine. 
- Gamified movement tracking: Your pet needs exercise! Take it on walks by going on a walk yourself! If your pet is not walked enough, its energy and happiness will drop accordingly.
- Sits on your desktop as a transparent overlay keeping it glanceable but not intrusive!

## TODO:

### Phase 1: Environment and OAuth setup
- [ ] Register application on Huawei Developer Console
- [ ] Enable Health Kit service and request `heartrate.read` and `step.read` scopes
- [ ] Set up local OAuth 2.0 redirect listener to capture authorization codes
- [ ] Implement access token exchange and refresh logic

### Phase 2: Core GUI
- [ ] Create a frameless, transparent window
- [ ] Set window property to `always-on-top`
- [ ] Add click-and-drag functionality so the user can position the pet anywhere
- [ ] Add simple context menu (Right Click -> Sync Data, Settings, Exit etc.)

### Phase 3: Pet Mechanics & Animations
- [ ] Create pet sprites (Aseprite)
- [ ] Import the pet sprites
- [ ] Create idle loop
- [ ] Implement pet health/happiness logic
- [ ] Add basic click interactions

### Phase 4: Huawei Health Integration
- [ ] Write API client to pull live heart rate samples
- [ ] Write API client to pull daily step totals
- [ ] Map heart rate thresholds to pet states
- [ ] Map step goal percentages to pet happiness levels

### Phase 5: Submission Readiness
- [ ] Test end-to-end user flow (launch -> Auth -> Desktop Pet -> Live sync)
- [ ] Record a 1-minuite demo video showing real-time response
- [ ] Finalize README