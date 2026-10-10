# Musician Website Backlog

Solomon King

## Project idea

A simple website where musicians can find people to work with. Users would make profiles, create posts, search for musicians, and connect outside the site.

This is a first pass of the requirements based on my idea. All items are planned and may change after getting feedback from musicians. ChatGPT helped generate the backlog.

## How to read it

- **High:** Needed for the basic version.
- **Medium:** Extra features if there is time.
- **Tag:** The part of the project the requirement belongs to.
- **Depends on:** Requirements that need to be in place first.

## Basic requirements

### R1: Accounts

Users can sign up, log in, and log out.

**Priority:** High · **Tag:** Account  
**Depends on:** None

### R2: Musician profiles

Users can create and edit a profile with their name, musician role, genres, and a short bio.

**Priority:** High · **Tag:** Profile  
**Depends on:** R1

### R3: Browse profiles

Users can browse musicians and open their profiles to learn more about them.

**Priority:** High · **Tag:** Profile  
**Depends on:** R2

### R4: Create posts

Users can post what kind of musician they need. Each post has a title, description, and role wanted, like producer or vocalist.

**Priority:** High · **Tag:** Posts  
**Depends on:** R2

### R5: Browse posts

Users can browse collaboration posts, read the full post, and open the creator's profile.

**Priority:** High · **Tag:** Posts  
**Depends on:** R3, R4

### R6: Edit or delete posts

Users can edit or delete their own posts.

**Priority:** High · **Tag:** Posts  
**Depends on:** R4

### R7: Search

Users can search profiles and posts by keywords.

**Priority:** High · **Tag:** Search  
**Depends on:** R3, R5

### R8: Filters

Users can filter profiles by role and genre. Posts can be filtered by the role wanted.

**Priority:** High · **Tag:** Search  
**Depends on:** R7

### R9: Show interest

Users can show interest in another person's post. The creator can accept or decline.

**Priority:** High · **Tag:** Connection  
**Depends on:** R1, R5

### R10: Share contact information

Users can save an email or social link privately. Showing interest and accepting it both mean agreeing to share those details. After acceptance, only the two users can see each other's contact information.

**Priority:** High · **Tag:** Connection  
**Depends on:** R2, R9

### R11: Security

Passwords must be stored as secure hashes. Users can only edit their own profiles and posts. Contact information stays private until both users agree to share it. These checks are added as each feature is built.

**Priority:** High · **Tag:** Security  
**Depends on:** R1, R2, R4, R10

### R12: Phone and computer layout

The main pages should be readable and easy to use on both phones and computers.

**Priority:** High · **Tag:** Usability  
**Depends on:** R3, R5, R8, R10

## Extra features

### R13: Music links

Users can add a link to their music on their profile.

**Priority:** Medium · **Tag:** Profile  
**Depends on:** R2

### R14: Save posts

Users can save posts to look at later and remove them from their saved list.

**Priority:** Medium · **Tag:** Posts  
**Depends on:** R1, R5

## Sprint plan

1. **Sprint 1:** Accounts and profiles (R1–R3).
2. **Sprint 2:** Creating, browsing, and editing posts (R4–R6).
3. **Sprint 3:** Search and filters (R7–R8).
4. **Sprint 4:** Connections and contact sharing (R9–R10), then checking the basic version.

Security and phone layout (R11–R12) would be checked while building each feature. Music links and saved posts (R13–R14) would be added if there is time.

## Keeping it manageable

I would leave out built-in messaging, payments, and music uploads for this term. I would still ask musicians which roles and filters they would actually use before treating this list as final.
