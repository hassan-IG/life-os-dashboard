# Changelog

## [4.0.0] — 2026-03-21

### Added — Premium Features
- Chart.js visualizations (8 interactive charts across 5 pages)
- - 365-day GitHub-style habit streak heatmap
  - - Weekly Review page with auto-generated insights and radar chart
    - - Data export (JSON + CSV) and import functionality
      - - Habit log system for historical tracking
       
        - ### Added — Core
        - - 9 interactive pages with full CRUD: Tasks, Goals, Fitness, Finance, Journal, Meals, Reading, Water, Wellness
          - - Light/dark mode with localStorage persistence
            - - Dashboard widgets: Journal quick-entry, Pomodoro timer, Water tracker
              - - Quick Access cards with live stats
                - - Hash-based routing (SPA)
                  - - Responsive design (desktop, tablet, mobile)
                   
                    - ### Charts
                    - - Finance: Expense category donut + Income vs Expenses bar
                      - - Goals: Horizontal progress bar chart
                        - - Fitness: Weekly habit completion bar + 365-day heatmap
                          - - Journal: Mood trend line chart
                            - - Review: Life balance radar + Habit streak bars
                             
                              - ### Technical
                              - - Single-file architecture (zero build tools)
                                - - React 18 via CDN with Babel transpilation
                                  - - Chart.js 4.4 for all visualizations
                                    - - CSS variables for theming
                                      - - LocalStorage for all data persistence
