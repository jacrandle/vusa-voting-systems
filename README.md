# 🏛️ VUSA Individual Voting System

**A realistic Congressional voting simulator with hierarchical vote weighting and real-time collaboration**

Transform how you understand Congressional power dynamics with this sophisticated political simulation that models actual legislative processes, from leadership influence to the Hastert Rule.

---

## 🎯 **Live Demo**
**[🚀 Try it now →](https://vusa-ivs.netlify.app/)**

*Experience realistic Congressional voting with real-time collaboration and authentic power structures*

---

## ✨ **Key Features**

### 🏛️ **Realistic Senate Voting**
- **Hierarchical Vote Weighting**: Party Leaders (25% of party votes), Whips (20%), Caucus Chairs (faction-based), Rank-and-File (1 vote each)
- **Proportional Leadership Tax**: Leadership bonuses drawn proportionally from all caucuses
- **Mathematical Precision**: Auto-scaling ensures exact party seat totals
- **Role-Based Power**: Authentic Congressional hierarchy with meaningful influence distribution

### 🏢 **Strategic House Voting** 
- **Faction-Based Voting**: Caucuses vote as unified blocs representing all members
- **Hastert Rule Analysis**: Real-time tracking of majority party vote requirements
- **Coalition Building**: Realistic faction dynamics and vote counting

### 🤝 **Real-Time Collaboration**
- **Google Sheets Integration**: Multi-user sessions with live data sync
- **Session Management**: Create, switch, and manage multiple scenarios
- **Offline Support**: Full functionality with local storage backup
- **Cross-Platform**: Works on desktop, tablet, and mobile

### 📊 **Advanced Analytics**
- **Live Vote Counting**: Real-time results with party breakdowns
- **Hastert Rule Compliance**: Automatic majority party threshold checking
- **Bill Status Tracking**: Pass/fail analysis with vote margins
- **Data Export**: JSON export for analysis and record-keeping

---

## 🎓 **Perfect For**

- **📚 Political Science Education**: Teach students how Congress really works
- **🏛️ Model Congress/UN**: Run realistic legislative simulations  
- **👨‍🏫 Civic Education**: Demonstrate legislative processes and power structures
- **🎮 Political Gaming**: Strategic voting games with authentic mechanics
- **📖 Research & Training**: Legislative staff training and academic research

---

## ⚖️ **How The Voting System Works**

### Senate Hierarchical Formula

Our voting system reflects real Congressional power dynamics:

```
Party Leader = 1 (self) + caucus share + 25% of party seats
Party Whip = 1 (self) + caucus share + 20% of party seats  
Caucus Chair = 1 (self) + remaining caucus seats after R&F
Rank-and-File = 1 vote (guaranteed representation)
```

**Leadership Tax**: The 45% leadership bonus (25% + 20%) is proportionally "taxed" from all caucuses based on their size.

**Scaling**: All votes are proportionally scaled to ensure the total exactly equals the party's actual seat count.

### Example Scenario (Republicans: 49 seats, 8 players)
- **Party Leader**: ~14 votes (significant influence)
- **Party Whip**: ~12 votes (deputy leadership)  
- **Caucus Chairs**: 5-8 votes each (faction control)
- **Rank-and-File**: 1 vote each (guaranteed voice)

### House Faction System
- Factions vote as unified blocs
- Each faction vote = all faction members
- Hastert Rule: Majority party must provide 50%+1 of their own votes

---

## 🛠️ **Tech Stack**

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Data Storage**: Google Sheets API + Local Storage
- **Authentication**: Google OAuth 2.0
- **Deployment**: Netlify (with auto-deploy from GitHub)
- **Offline Support**: Progressive Web App features

---

## 🚀 **Getting Started**

### Quick Start (No Setup Required)
1. **[Open the app](https://vusa-ivs.netlify.app/)**
2. **Create factions**: Add political caucuses with seat counts
3. **Add senators**: Assign roles (Party Leader, Whip, Chair, Rank-and-File)  
4. **Start voting**: Cast votes and watch real-time results
5. **Analyze results**: Review Hastert Rule compliance and vote margins

### Collaborative Sessions
1. **Click "🔑 Authorize"** to connect Google Sheets
2. **Create a new session** or join an existing one
3. **Share the session** with other participants
4. **Vote together** with real-time synchronization

### Offline Mode
- Works completely offline with browser storage
- **Export data** as JSON files for backup
- **Import sessions** to restore or share scenarios

---

## 📖 **Usage Examples**

### Political Science Classroom
```
1. Set up realistic party composition (e.g., 51 R, 49 D)
2. Create factional caucuses (Freedom Caucus, Progressive Caucus, etc.)
3. Assign student roles with authentic vote weights
4. Vote on hypothetical bills and analyze outcomes
5. Discuss how leadership structure affects legislation
```

### Model Congress
```
1. Mirror actual Congressional composition
2. Assign delegates to realistic factions
3. Vote on real or simulated legislation
4. Experience authentic power dynamics
5. Learn coalition-building strategies
```

---

## 🏗️ **Architecture**

### Vote Weight Calculation
```javascript
// Simplified calculation flow
1. Calculate base caucus shares for each faction
2. Assign party leadership bonuses (Leader: 25%, Whip: 20%)
3. Apply proportional "tax" across all caucuses
4. Distribute remaining seats to caucus chairs
5. Guarantee 1 vote for all rank-and-file
6. Scale proportionally to exact party totals
```

### Data Flow
```
User Input → Vote Calculation → Results Display
     ↓              ↓              ↓
Local Storage ← Google Sheets → Real-time Sync
```

---

## 🤝 **Contributing**

We welcome contributions! This project is perfect for:

- **Political scientists** who understand legislative processes
- **Developers** interested in civic technology
- **Educators** with simulation experience
- **Students** learning about government

### Ways to Contribute
- 🐛 **Bug reports** and feature requests
- 📚 **Documentation** improvements  
- 🎨 **UI/UX** enhancements
- ⚖️ **Formula refinements** based on political science research
- 🌐 **Internationalization** for other legislative systems

---

## 📄 **License**

MIT License - feel free to use, modify, and distribute for educational purposes.

---

## 🎯 **Roadmap**

- [ ] **Committee System**: Add committee voting and markup processes
- [ ] **Amendment Process**: Support for bill amendments and substitutes  
- [ ] **Lobbying Simulation**: Add external influence mechanics
- [ ] **Historical Scenarios**: Pre-built historical vote recreations
- [ ] **International Legislatures**: Support for parliamentary systems
- [ ] **Mobile App**: Native iOS/Android versions
- [ ] **AI Opponents**: Computer-controlled factions for solo play

---

## 📞 **Contact & Support**

- **Issues**: [GitHub Issues](https://github.com/yourusername/vusa-voting/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/vusa-voting/discussions)  
- **Email**: virtualgovownership@gmail.com

---

## 🙏 **Acknowledgments**

- Inspired by real Congressional procedures and power structures
- Built for educators, students, and civic engagement
- Special thanks to the political science community for feedback

---

**⭐ If this helps your teaching or learning, please star the repo!**

*Making democracy more understandable, one vote at a time.*
