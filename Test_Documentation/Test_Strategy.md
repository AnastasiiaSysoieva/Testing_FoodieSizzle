Platform: iOS

1. Testing Objective
    
    The objective of testing is to ensure stable gameplay, correct game mechanics, and positive user experience by identifying functional, usability, and performance issues before release.
    
2. Testing Approach
    
    Testing will be performed using a combination of:
    
- Functional testing
- Exploratory testing
- Regression testing
- Smoke testing
- UI/UX testing
- Compatibility testing on iOS devices

Priority is given to core gameplay mechanics and player progression systems.

3. Test Levels
- Feature testing (individual mechanics)
- Integration testing (interaction between systems)
- End-to-end testing (full gameplay flow)
4. Test Types
- Manual testing (primary approach)
- Usability testing
- Negative testing
- Interrupt testing (calls, background mode, internet loss) “Переривання”
- Session-based exploratory testing
- Testing the installation
- Internet connection ( WI-Fi, 2g, 3g, 4g, 5g)
5. Test Environment
- iOS mobile devices
- Different network conditions (Wi-Fi, mobile data, offline)
- Production-like environment
6. Tools
- Notion (documentation)
- Jira (bug tracking)
- Screen recording tools for defect reproduction
7. Risk-Based Testing
    
    Higher priority testing areas:
    
- Life (energy) system
- Reward calculations
- Timer mechanics
- Customer order logic
- Purchases and currency balance
8. Defect Management
    
    All defects are logged in Jira with severity and priority levels.
    
    Critical and Blocker issues must be fixed before release.
    
9. Entry and Exit Strategy
    
    Testing begins when the build is stable and installable.
    
    Testing ends when exit criteria from Test Plan are satisfied.
    
10. Metrics
- Number of defects by severity
- Test case pass rate
- Regression success rate
- Critical defect leakage
