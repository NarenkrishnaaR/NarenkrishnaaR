```//
//  Naren.swift
//  GitHubProfile
//
//  Created by Naren on 2024.
//  🚀 Passionate iOS Developer | Swift Enthusiast | Lifelong Learner
//

import Foundation

struct Naren {
  
  // MARK: - About Me
  let name: String = "Naren Krishnaa"
  let role: String = "Senior iOS Developer"
  let experience: Int = 8
  
  // MARK: - Current Focus
  var currentFocus: [String] {
    return [
      "📚 Deepening expertise in SwiftUI and Combine",
      "🚀 Enhancing iOS performance with Core Animation and optimization techniques",
      "🎨 Crafting clean and scalable UI/UX designs",
      "🎙️ Exploring podcast integration and multimedia content delivery",
      "📖 Sharing knowledge through blogs and Swift meetups",
      "📚 Enjoying fiction and exploring new literary genres"
    ]
  }
  
  
  // MARK: - Skills
  let skills: [String] = [
    // Programming Languages & Frameworks
    "Swift", "Objective-C", "UIKit", "SwiftUI",
    
    // Data Persistence & Storage
    "Core Data", "Realm", "Firebase",
    
    // Architectural Patterns
    "MVP", "MVC", "MVVM",
    
    // Version Control & Deployment
    "Git", "GitHub", "App Store Deployment",
  ]
  
  
  // MARK: - Connect With Me
  func connectLinks() -> [String: URL] {
    return [
      "💼 LinkedIn": URL(string: "https://www.linkedin.com/in/narenkrishnaa")!,
      "🐙 GitHub": URL(string: "https://github.com/NarenkrishnaaR")!,
      "📧 Email": URL(string: "mailto:narenkrishnaar@gmail.com")!
    ]
  }
}
  // Instantiate the Profile
  let narenProfile = Naren()
  
  // Showcase Profile Details
  print("👋 Hello, I'm \(narenProfile.name) - \(narenProfile.role) with \(narenProfile.experience)+ years of experience.\n")
  print("🚀 Currently focusing on: \(narenProfile.currentFocus.joined(separator: ", "))\n")
  print("🛠️ Skills: \(narenProfile.skills.joined(separator: ", "))\n")
  print("📬 Connect with me: \(narenProfile.connectLinks().keys.joined(separator: ", "))\n")
    
