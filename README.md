# zKillCrawler Bot Capabilities 🤖

## 🚀 [TRY THE BOT NOW](https://discord.gg/G9eu4vsHQg)

## 🎯 Core Functions

### 📡 Real-time Killmail Monitoring
- **Live Feed Processing**: Monitors zkillboard's RedisQ stream for instant killmail notifications
- **Multi-Channel Support**: Multiple independent feeds per Discord channel with unique configurations
- **Rich Embeds**: Beautiful, detailed killmail displays with clickable links and comprehensive information
- **High Throughput**: Processes 1,000+ killmails per hour with sub-2-second response times

### 🔍 Advanced Filtering System (15+ Filter Types)

#### 👥 Entity Filters
- **Character Filters**: Target specific pilots by name or character ID
- **Corporation Filters**: Monitor specific corporations with intelligent name resolution
- **Alliance Filters**: Track alliance-wide activity with automatic member detection
- **Intelligent Resolution**: Auto-resolves names to IDs with fuzzy matching and suggestions

#### 🚢 Ship & Combat Filters
- **Victim Ship Filters**: Filter by specific ship types, groups, or categories
- **Attacker Ship Filters**: Monitor what ships are doing the killing
- **Ship Group Expansion**: Automatic expansion of ship groups (e.g., "Titan" includes all titan types)
- **AT Ship Preset**: One-click Alliance Tournament ship tracking
- **Attacker Count Ranges**: Filter by fleet size (1-50+ attackers)

#### 🌍 Location & Distance Filters
- **System Filters**: Monitor specific solar systems by name or ID
- **Region Filters**: Track entire regions with automatic system inclusion
- **Security Class Filters**: 
  - **Highsec** (0.5-1.0 security)
  - **Lowsec** (0.1-0.4 security)  
  - **Nullsec** (-1.0 to 0.0 security, non-wormhole)
  - **J-space** (Wormhole systems: J123456, Thera, C-class)
  - **Pochven** (Triglavian space)
- **Distance-based Filtering**:
  - **Lightyear Distance**: Within X LY of reference system
  - **Jump Distance**: Within X gate jumps of reference system

#### 💰 Value & Economics Filters
- **ISK Value Ranges**: Filter by kill value with intuitive notation
  - Support for "10b" (10 billion), "500m" (500 million), "1.5b" formats
  - Minimum and maximum value thresholds

#### 🎯 Faction Warfare Integration
- **FW System Status**: Filter by contested, vulnerable, or captured systems
- **Faction Filters**: Monitor specific faction activity
- **Dynamic Updates**: Real-time FW system status updates from ESI

### 🛡️ Gatecamp Detection System

#### 🧠 Intelligent Pattern Recognition
- **Proximity Analysis**: Uses precise ESI stargate coordinates (within 10km detection)
- **Overlap Detection**: Multi-layered attacker correlation:
  - Character-level overlap (highest priority)
  - Corporation-level overlap (secondary)
  - Alliance-level overlap (fallback)
- **Time Window Analysis**: 2-hour rolling window for persistent camp detection
- **Fleet Fight Protection**: Smart detection to prevent false alerts during large battles

#### 🔔 Real-time Alerting
- **Live Timer Updates**: Continuous timer updates showing gatecamp duration (15-minute max)
- **Distance Integration**: Shows distance from your reference system in lightyears
- **Comprehensive Details**: Camp location, involved entities, victim statistics
- **Historical Tracking**: Persistent storage for pattern analysis

#### ⚙️ Configuration Options
- **Reference System Setup**: Choose your staging system for distance calculations
- **Per-Channel Configuration**: Independent gatecamp monitoring per Discord channel
- **Dropdown Management**: Easy enable/disable via interactive menus

## 📊 Analytics & Intelligence

### 📈 Feed Analytics
- **Top Systems**: Most active systems for each feed
- **Ship Type Analysis**: Popular victim and attacker ships
- **Entity Statistics**: Most active characters, corporations, alliances
- **Time-based Trends**: Activity patterns and peak hours
- **Value Tracking**: ISK destroyed over time

### 📋 Intel Reports
- **Interactive Analytics**: Rich Discord embeds with detailed statistics
- **Historical Data**: Persistent storage of all matched killmails
- **Feed Performance**: Statistics on filter effectiveness and match rates

## 🎮 Discord Commands

### 🔧 Feed Management Commands
| Command | Description | Permissions |
|---------|-------------|-------------|
| `/addfeed <name>` | Create new killmail feed with interactive filter setup | Manage Server |
| `/editfeed` | Modify existing feed filters with guided interface | Manage Server |
| `/stopfeed` | Delete feeds from current channel via dropdown | Manage Server |

### 🛡️ Gatecamp Commands
| Command | Description | Permissions |
|---------|-------------|-------------|
| `/gatecamp-enable <system>` | Enable gatecamp detection for specified reference system | Manage Server |
| `/gatecamp-disable` | Disable gatecamp detection with dropdown selection | Manage Server |

### 📊 Analytics Commands
| Command | Description | Permissions |
|---------|-------------|-------------|
| `/intel` | View comprehensive feed analytics and reports | None |
| `/fwleaders` | Display faction warfare leaderboards and statistics | None |

## 🎨 User Experience

### 🖥️ Interactive Interfaces
- **Filter Setup Wizard**: Guided filter creation with real-time validation
- **Dropdown Menus**: Easy feed management and selection
- **Button Interactions**: Confirmation dialogs and action buttons
- **Autocomplete**: Intelligent suggestions for entity names and IDs

### 📱 Rich Discord Integration
- **Embed Formatting**: Beautiful, consistent message formatting
- **Color Coding**: Visual distinction between security classes and ship types
- **Emoji Integration**: Clear visual indicators for different data types
- **Link Generation**: Clickable links to zkillboard, ships, systems, and entities

### 🔔 Smart Notifications
- **Intelligent Grouping**: Avoids spam during high-activity periods
- **Priority System**: Important kills highlighted appropriately
- **Context Preservation**: Maintains feed attribution and source information
- **Error Recovery**: Graceful handling of API outages with backlog processing

## 🎯 Use Cases

### 🏢 Corporation/Alliance Management
- Monitor member activity and losses
- Track enemy movements in your space
- Analyze combat effectiveness and ship usage
- Detect potential threats via gatecamp alerts

### 🎣 Content Hunting
- Find active PvP systems and regions
- Track high-value targets and routes
- Monitor faction warfare activity
- Identify gatecamp opportunities

### 📊 Market Intelligence
- Track ship loss trends for market predictions
- Monitor capital ship movements
- Analyze regional economic activity
- Identify emerging combat metas

### 🛡️ Security Operations
- Early warning systems for your territory
- Automated threat detection and alerting
- Intelligence gathering on hostile entities
- Strategic movement monitoring


